# Reversing a string in C
A #string in #C can be defined by
```c
char str[5] = "This is a string!";
```
I will demonstrate a few ways to reverse this string.

## Copying characters to buffer
This algorithm is the easiest to both implement and understand, however it uses more memory than in-place swapping.

### Implementation
```c
void reverse(char* in, char* out, int len) {
	int i, j = 0;
	for (int = len - 1, i >= 0; i--) {
		*(out + j) = *(in + i);
		j++;
	}
	*(out + len) = '\0';
} 
```
### Description
**i** is used to peek through input array from end to start, and **j** is used to address each element of output array.
We take each element of input array starting from its end, and place them in output array.
At the last line we append a null character that indicates a string is complete. Not appending this will result in terrible bugs when printing the output array.

## Swapping contents
Pretty weird code, even though I am the author...

### Implementation
```c
void reverse(char* in, int len) {
	int i = len - 1, j = 0;
	char swap;
	for (; i >= 0; i--) {
		if (j == i + 1 - (len % 2))
			break;
		swap = *(in + i);
		*(in + i) = *(in + j);
		*(in + j) = swap;
		j++;
	} 
}
```
### Description
Oh boy... I don't think I am capable of describing this one in English. 
**i** and **j** do the same as above, but **swap** is new here, it is used to temporarily hold the value of upper element (the element that is indexed by **i**) while value indexed by **j** is copied to value indexed by **i**.
```c
swap = arr[i];
arr[i] = arr[j];
arr[j] = swap;
```
And then we enter to a for loop, which iterates over the **in** array from end to start using **i**. Before executing the 3-line-long-swap operation we perform a weird check to see if we are in the middle of the array. This is necessary to not swap array from start to end. "*WHY?*", you might be asking, so here's why:
If you continue to keep swapping after you reach middle, you will start to place the initial values back to where they belong, and we definitely don't want this. I actually got stuck at this point, trying to figure out why I couldn't manipulate my string. Turns out everything was *swapped to perfection* :)

Breakdown of the statement in if:
When determining if we have swapped enough characters, there are two different states which depend on total character count.
![[Pasted image 20220528230826.png]]
- If there is even amount of characters, excluding null character, when **j** equals **i** + 1, next step will swap one character back to its initial position.
![[Pasted image 20220528230714.png]]
- If there is odd amount of characters, excluding null character, when **j** equals **i**, we reach the middle of our array.
To mathematically (and programmatically) express this statement, one can say that "j = i + 1 - (len % 2)". If there is even amount of characters (len % 2) will be 0, else (len % 2) will be 1, which ultimately makes the if condition "j = i + 1 - 1"

Alright, that's it!