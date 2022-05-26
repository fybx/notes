## Tanım
$V$, $K$ cismi üzerinde bir [[Vektör Uzayı]]dır. $v_1,v_2,v_3,...,v_n\in V$ için $\sum_{i=1}^{n} c_iv_i=0\Rightarrow\forall c_i=0$ ise $v_1,v_2,v_3,...,v_n$ [[Vektör]]leri *lineer bağımsızdır*, aksi halde [[Lineer Bağımlılık]] vardır.

Diğer bir ifadeyle, eğer $v_1,v_2,v_3,...,v_n$ lineer bağımlı ise $\sum_{i=1}^{n} c_iv_i=0$ olacak şekilde hepsi birden sıfır olmayan $c_1,c_2,c_3,...,c_n$ skalarları vardır.

Lineer bağımsızlık [[Uzayı Germe]]nin şartıdır. Lineer bağımsız vektörler birbirine eklenip çıkartılarak uzaydaki tüm vektörler elde edilebilir.

**Dikkat: Lineer bağımsız kümeler $0$ elemanını içine almayan kümelerdir.** $0$ elemanını bulunduran herhangi bir küme doğal olarak lineer bağımlıdır.

## Tespit
#### Yöntem 1:
$c_1v_1+c_2v_2+...+c_nv_n=0$ tek bir ihtimalde mümkünse ve bu ihtimalde $c_1=c_2=...=c_n=0$ ise $v_1,v_2,...,v_n$ lineer bağımsızdır. Herhangi bir c değeri sıfırdan farklı olursa vektörler lineer bağımlıdır.

###### Örnek 1:
$\mathbb{R}^2$ vektör uzayında $A=\lbrace a_1=(1,2), a_2=(2,4)\rbrace$, $B=\lbrace b_1=(1,2), b_2=(1,1)\rbrace$ kümelerinin lineer bağımsız olup olmadığını belirleyiniz.
1. $A$: $-2a_1+a_2=(0,0)=0$ olduğundan $A$ kümesi lineer bağımlıdır.
2. $B$: $c_1(1,2)+c_2(1,1)=0=(0,0)$ çözümü yapılmalıdır. $c_1=0$ ve $c_2=0$ bulunduğundan $B$ kümesi lineer bağımsızdır.

###### Örnek 2:
$v_1=(1,3)$ ve $v_2=(2,6)$ lineer bağımlı mıdır?
$c_1+2c_2=0$ ve $3c1+6c2=0$ sistemlerinin çözümünden $c_1=c_2=0$ olduğu bulunur. $v_1$ ve $v_2$ lineer bağımlıdır.

#### Yöntem 2:
Verilen vektörler sütunlara yerleştirildiğinde kare matris oluşursa bu yöntemi kullanabilirsin.
$A=\left[ { \begin{array}{cc} v_1 & v_2 \end{array}} \right]$ için $detA=0$ ise *lineer bağımlı*, değilse *lineer bağımsızdır*.

###### Örnek 3:
$v_1=(1,1)$ ve $v_2=(2,-3)$ lineer bağımlı mıdır? Determinant yöntemi ile kontrol et.
$A=\left[ { \begin{array}{cc} 1 & 2 \\ 1 & -3 \end{array}} \right]$, $detA=1\cdot(-3)-2\cdot1\neq0$ olduğu için lineer bağımsızdır.

## Örnekler:
###### Örnek 4:
$E=\lbrace1,1+x,1-x,x^2\rbrace$ kümesinin elemanları lineer bağımlı mıdır?
$c_1\cdot1+c_2(1+x)+c_3(1-x)+c_4(x^2)=0$ iken $c_1=c_2=c_3=c_4=0$ ise lineer bağımlıdır.
$c_1+c_2+xc_2+c_3-xc_3+x^2c_4=0$ biçiminde elde ettiğimiz polinomun sıfır olması için:
1. $c_4=0$
2. $c_2-c_3=0$
3. $c_1+c_2+c_3=0$ olmalıdır.
$\therefore c_1+2c_2=0$ elde edilir. Bu denklemde sonsuz farklı $c_1$ ve $c_2$'ler elde edilir ve en baştaki koşul sağlanamaz. $E$ kümesinin elemanları lineer bağımlıdır.

###### Örnek 5:
$A=\left[\begin{array}{cc} 1&2\\0&1 \end{array}\right]$, $B=\left[\begin{array}{cc} -1&0\\1&1 \end{array}\right]$, $C=\left[\begin{array}{cc} 1&3\\2&0 \end{array}\right]$ matrisleri lineer bağımlı mıdır?
![[IMG_lineerbagimsizlikcozum.jpg]]
$c_1=c_2=c_3=0\therefore A,B,C$ lineer bağımsızdır.