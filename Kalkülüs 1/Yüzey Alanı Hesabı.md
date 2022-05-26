## Tanım
$f(x)$, $[a,b]$ aralığında tanımlı, $\forall x\in[a,b]$ için $f(x)\geq0$ ve $f'(x)$ mevcut olsun. Bu durumda, aralıkta kalan eğrinin seçilen eksen etrafında döndürülmesi ile oluşan cisme dönel cisim denir.

Cismin yüzey alanının hesabı yapılırken eğrinin etrafında döndürüldüğü eksene göre kullanılacak formül belirlenir. 

### x-ekseni etrafında döndürülme
$y=f(x)$, $a\leq x\leq b$ eğrisi x-ekseni etrafında döndürülüyorsa oluşan yapının yüzey alanı 
- $S=2\pi \int_a^b f(x)\sqrt{1+[f'(x)]^2}dx$ $br^2$
olarak hesaplanır.

###### Örnek 1:
$f(x)=\sqrt{16-x^2}$ eğrisinin $[-4,0]$ aralığındaki yayının x-ekseni etrafında döndürülmesiyle oluşan dönel cismin yüzey alanını hesaplayınız.
###### Çözüm 1:
İlk olarak $f'(x)$ değerini bulalım. $f'(x)=\frac{-2x}{2\sqrt{16-x^2}}=-\frac{x}{\sqrt{16-x^2}}$ ve $[f'(x)]^2=\frac{x^2}{16-x^2}$. Bu değerleri formülde yerine yazalım. $S=2\pi\cdot\int_{-4}^0 \sqrt{16-x^2}\sqrt{1+\frac{x^2}{16-x^2}}dx$. Şimdi bu iğrenç görünümlü şeyi çözeceğiz. Sadece iki kareköke konsantre ol, ikisini çarp: $\sqrt{(16-x^2)\cdot(1+\frac{x^2}{16-x^2})}$, ikinci parantezin içini yap $\sqrt{(16-x^2)\cdot\frac{16}{16-x^2}}=\sqrt{16}=4$. Bu güzel sonucu integrale geri götür. $S=8\pi\int_{-4}^0 dx=8\pi(x|_{-4}^0)=(0-(-4))\cdot8\pi=32\pi$ $br^2$.
![[Pasted image 20220526202715.png]]

### y-ekseni etrafında döndürülme
$y=f(x)$, $a\leq x\leq b$ eğrisi x-ekseni etrafında döndürülüyorsa oluşan yapının yüzey alanı 
 - $S=2\pi \int_a^b x\sqrt{1+[f'(x)]^2}dx$ $br^2$ 
olarak hesaplanır.

###### Örnek 1:
$y=\sqrt{16-x^2}$ eğrisinin $[0,\sqrt7]$ aralığında kalan parçasının y-ekseni etrafında döndürülmesi ile oluşan cismin yüzey alanı kaç birimkaredir?
###### Çözüm 1:
Öncelikle $y'$ ifadesini hesaplayalım. $y'=\frac{-2x}{2\sqrt{16-x^2}}=-\frac{x}{\sqrt{16-x^2}}$ olduğunu kolayca hesaplayabiliyor olmalısın. Şimdi formülü kullanma zamanı. $S=2\pi\int_0^\sqrt7 x\sqrt{1+(-\frac{x}{\sqrt{16-x^2}})^2}dx$
$=2\pi\int_0^\sqrt7 x\sqrt{1+\frac{x^2}{16-x^2}}dx$
$=2\pi\int_0^\sqrt7 x\sqrt{\frac{16}{16-x^2}}dx$
$=2\pi\int_0^\sqrt7 \frac{4x}{\sqrt{16-x^2}}dx$
Burada çözüme devam etmeden önce küçük bir değişken değiştirmece yapmakta fayda var. Dışarıdaki $x$ ile içerideki $16-x^2$ güzel bir uyuma sahip. $u^2=16-x^2$ dolayısıyla da $2udu=-2xdx$, böylece
$=2\pi\int_0^\sqrt7 (\frac{4x}{\sqrt{u^2}}\frac{u}{-x})du$, parantez içinin birbirine girip çıkınca $-4du$ kaldığını hissetmelisin.
$=-8\pi\int_0^\sqrt7 du$. **AMAN DİKKAT** Sınırların $dx$'e göre olduğunu unutup düz devam edersen yandın. Sınırları yeniden hesaplayalım:
$=-8\pi\int_4^3 du=-8\pi(u|_4^3)=-8\pi(-1)=8\pi$ $br^2$.
![[Pasted image 20220524230652.png]]