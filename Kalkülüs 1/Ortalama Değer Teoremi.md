## Tanım
İntegrallerin kullanıldığı alanlardan bir bir diğeri de $y=f(x)$ fonksiyonunun istenen bir $[a,b]$ aralığındaki ortalama değerini bulmaktır.

Bir $f$ fonksiyonunun $[a,b]$ aralığındaki ortalama değeri $\overline{f}=\frac{1}{b-a}\int_a^b f(x)dx$ biçiminde tanımlanır.

Bu tanımdan yola çıkarak şu teorem ortaya atılır: $[a,b]$ aralığında en az bir $c$ noktası vardır ki o noktada $f(x)$, ortalama değer $\overline{f}$'e eşittir.

![[Pasted image 20220524232150.png]]

## Örnekler
###### Örnek 1:
$f(x)=x^2$ eğrisinin $[0,3]$ aralığındaki ortalama değeri ve bu değere eşit olduğu $c$ noktasını bulunuz.
###### Çözüm 1:
Öncelikle ortalama değeri hesaplayalım. $\overline{f}=\frac{1}{3-0}\int_0^3 x^2dx$
$=1/9\cdot(x^3|_0^3)=1/9\cdot27=3$.
$f(c)=c^2=3\therefore c=\sqrt{3}$.

###### Örnek 2:
$f(x)=\sqrt{x+3}$ eğrisinin $[1,6]$ aralığındaki ortalama değerini ve bu değere eşit olduğu $c$ noktasını bulunuz.
###### Çözüm 2:
Alışılageldik, sıkıcı yöntemler... $\overline{f}=\frac{1}{6-1}\int_1^6 (\sqrt{x+3})dx$, minik bir $u=x+3$ ve $du=dx$
$=\frac{1}{5} \int_1^6 u^{1/2}du$
$=\frac{1}{5}\cdot\frac{2}{3}\cdot((x+3)^{3/2}|_1^6)$ 
$=\frac{2}{15}\cdot(\sqrt{9^3}-\sqrt{4^3})$
$=\frac{2\cdot(3^3-2^3)}{15}=38/15$.
	Ve elbette $f(c)=\sqrt{c+3}=38/15$ ki korkunç biçimde $c=\frac{38^2-3\cdot15^2}{15^2}=\frac{769}{225}$.