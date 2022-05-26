Dönel cisim, bir $f(x)$ eğrisi, bir eksen etrafında döndürüldüğünde meydana gelen yapıdır.

### x-ekseni etrafında döndürülme
$y=f(x)$, $a\leq x\leq b$ eğrisi x-ekseni etrafında döndürülüyorsa oluşan yapının yüzey alanı $S=2\pi \int_a^b f(x)\sqrt{1+[f'(x)]^2}dx$ $br^2$ olarak hesaplanır.

### y-ekseni etrafında döndürülme
$y=f(x)$, $a\leq x\leq b$ eğrisi x-ekseni etrafında döndürülüyorsa oluşan yapının yüzey alanı $S=2\pi \int_a^b x\sqrt{1+[f'(x)]^2}dx$ $br^2$ olarak hesaplanır.

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