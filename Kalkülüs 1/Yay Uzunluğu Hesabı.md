İntegralin kullanıldığı bir başka alan da, fonksiyonların grafiklerindeki yayların uzunluğunun hesaplanmasıdır.

## Tanım
$[a,b]$ aralığında sürekli ve türevli bir $f(x)$ fonksiyonunun, aralıklar arasında kalan parçasının uzunluğu $L=\int_a^b \sqrt{1+(f'(x))^2}dx$ şeklinde hesaplanır. Burada $f'(x)$, $f$ fonksiyonunun türevidir.

## Örnekler
###### Örnek 1:
$y=2x$ yayının $[0,5]$ aralığında kalan parçasının uzunluğu kaç birimdir?
###### Çözüm 1:
$L=\int_0^5 \sqrt{1+[(2x)']^2}dx$ integralinin çözümü yapılır. $L=[\int \sqrt{5}dx]|_0^5$
$=x\sqrt5|_0^5$
$=5\sqrt5$ br.

###### Örnek 2:
$y=\sqrt{4-x^2}$ yayının $[0,2]$ aralığında kalan parçasının uzunluğu kaç birimdir?
###### Çözüm 2:
Önce $y'$'i tespit edeceğiz. $y'=\frac{-2x}{2\sqrt{4-x^2}}=\frac{-x}{\sqrt{4-x^2}}$. Şimdi karesini alacağız ve $L$ bağıntısında yerine yazacağız. $(y')^2=\frac{x^2}{4-x^2}$
 $L=\int_0^2 \sqrt{1+\frac{x^2}{4-x^2}}dx$ bağıntısını çözmek için Trigonometrik [[Değişken Değiştirme]] uygulayacağız. $x=2sina$ ve $dx=2cosada$ elde edilecek.
 $L=\int_0^2 \sqrt{\frac{4}{4-x^2}}dx=\int_0^2 \sqrt{\frac{4}{4(1-sin^2 a)}}dx$
 $=\int_0^2 \frac{2cosada}{cosa}$
 $=2\int_0^2 da$. Bu noktada $a$'ya bağlı integralin sınırlarını düzelteceğiz.
 $L=2\int_\pi^{3\pi/2} da$
 $=2(a|_\pi^{3\pi/2})$
 $=2(\frac{3\pi}{2}-\pi)$ 
 $\pi$ br.

###### Örnek 3:
$f(x)=\frac{2x^{3/2}}{3}$ fonksiyonunun $[0,4]$ aralığında kalan parçasının uzunluğu kaç birimdir?
###### Çözüm 3:
$y'=\frac{2}{3}\frac{3}{2}x^{1/2}$. $[y']^2=x$ olduğunu görüyorsun. $L=\int_0^4 \sqrt{1+x}dx$ integralinin çözümünü [[Değişken Değiştirme]] ile çözeceğiz.
$u=x+1$ ve $du=dx$ olacak. $L=\int_0^4 u^{1/2}dx$
$=\frac{2}{3}(u^{3/2}|_1^5)$. Bu noktada sınırları yeni değişken $u$'ya göre ayarladığımıza dikkat et.
$L=\frac{10\sqrt5-2}{3}$ br.

###### Örnek 4:
$y=\frac{1}{4}x^4+\frac{1}{8x^2}$ yayının $[2,3]$ aralığında kalan parçasının uzunluğu kaç birimdir?
###### Çözüm 4:
$y'=x^3-\frac{1}{4x}$. $[y']^2=x^6-\frac{1}{2}+\frac{1}{16}x^{-6}$ olacak. $L=\int_2^3 \sqrt{1+x^6-\frac{1}{2}+\frac{1}{16}x^{-6}}dx$. Kemerlerini bağla, buradan sonrası manyaklaşacak.
$L=\int_2^3\sqrt{x^6+\frac{1}{16x^{6}}+\frac{1}{2}}dx$ . Burada iç kısmı $\frac{1}{16}$'ya böleceğiz. Neden diye sorma.
$L=\int_2^3\sqrt{\frac{1}{16}(16x^6+\frac{1}{x^{6}}+8)}dx$
$L=\int_2^3 \frac{1}{4}\sqrt{(16x^6+\frac{1}{x^{6}}+8)}$Şimdi parantez içindeki kısma odaklanalım. İşleri halledince tekrar yerine koyacağız.
Herkesi tek paydada ($x^6$) toplayarak başlayacağız. $\frac{16x^{12}+1+8x^6}{x^6}$ olduğunu görmelisin. Şimdi pay kısmının çarpanlarına ayrılmasını sağlamalıyız.
$t=x^6$ diyerek daha kolay bir yazım sağlayalım. $\frac{16t^2+8t+1}{t}$ olacak. Pay kısmını istersen kuadratik formülle, istersen de yandan yemiş çarpım bulucu algoritmayla çöz. $\frac{(4t+1)^2}{t}=\frac{(4x^6+1)^2}{x^6}$ olacağını gördün herhalde. Şimdi bu sapsade ifadeyi aldığımız parantezlere geri bırakalım.
$L=\frac{1}{4}\int_2^3 \sqrt{\frac{(4x^6+1)^2}{x^6}}dx$ şimdi sadeleşecek. $L=\int_2^3 \frac{4x^6+1}{x^3}dx$
$=\frac{1}{4}\int_2^3 (4x^3+x^{-3})dx$
$=\frac{1}{4}([x^4-\frac{1}{2x^2}]|_2^3)$
$=\frac{1}{4}[(81-\frac{1}{18})-(16-\frac{1}{8})]$ br
$\simeq16.267$ br.