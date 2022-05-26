## Tanım
Bir [[Vektör Uzayı]] $V$'den bir başka vektör uzayı $W$'ye tanımlı fonksiyon $f$'e *dönüşüm fonksiyonu* denir ve $v\in V,w\in W,T:V\longmapsto W\Rightarrow T(v)=w$ şeklinde tanımlanır.

Dönüşüm fonksiyonunun *doğrusal dönüşüm fonksiyonu* olarak sınıflandırılabilmesi için şu şartlar sağlanmalıdır:
1. $T(v+u)=T(v)+T(u)$
2. $T(cv)=cT(u)$

- Çarpılan, kuvveti alınan parametreler doğrusallığı bozar.

## Örnekler
###### Örnek 1:
$T(x,y)=(x+y,2x-y,y)$, $T:\mathbb{R}^2\mapsto\mathbb{R}^3$ tanımlı fonksiyonun doğrusal dönüşüm olduğunu gösteriniz.
1. $u=(x_1,y_1),v=(x_2,y_2)$ seçilsin. $T(u+v)=T(x_1+x_2,y_1+y_2)=(x_1+x_2+y_1+y_2, 2x_1+2x_2-y_1-y_2, y_1+y_2)$ ifadesi $T(u)+T(v)=(x_1+y_1, 2x_1-y_1,y_1)+(x_2+y_2, 2x_2-y_2,y_2)$ ifadesine eşittir. Birinci şart sağlanır.
2. $c\in\mathbb{R}$ ve $u=(x,y)$ seçilsin. $T(cu)=(cx+cy,2cx-cy,cy)$ ifadesi $cT(u)=c(x+y,2x-y,y)=(cx+cy,2cx-cy,cy)$ ifadesine eşittir. İkinci şart da sağlanır. $\therefore T$ doğrusal bir dönüşüm fonksiyonudur.

###### Örnek 2:
$T(x,y,z)=(x+y+2z,x^2+y^2)$ fonksiyonunun lineer dönüşüm fonksiyonu olup olmadığını belirleyiniz.
1. $u=(a,b,c)$ ve $v=(d,e,f)$ vektörleri ile $c\in\mathbb{R}$ skaleri seçilsin.
2. Birinci şart $T(u+v)=T(u)+T(v)$ sağlanmasıdır. (1) $T(u+v)=T(a+d,b+e,c+f)=(a+d+b+e+2c+2f,(a+d)^2+(b+e)^2)$ ifadesi elde edilir. (2) $T(u)+T(v)=(a+b+2c,a^2+b^2)+(d+e+2f,d^2+e^2)=(a+d+b+e+2c+2f,a^2+b^2+d^2+e^2)$ ifadesi elde edilir. (1) ve (2) birbirine eşit olmadığına göre birinci şart sağlanmaz. $T$ lineer dönüşüm değildir.