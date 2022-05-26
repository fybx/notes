Bir dönen cismin hacmi
1. [[Hacim Hesabı#Disk Dilimleme Yöntemi]] veya
2. [[Hacim Hesabı#Silindirik Kalıp Yöntemi]] ile bulunur.

### Disk (Dilimleme) Yöntemi
Bir $y=f(x)$ fonksiyonunun $[a,b]$ aralığındaki yayı ile $y=k$ doğrusu arasında kalan bölgenin $y=k$ etrafında döndürülmesiyle oluşan dönen cismin hacmi $V=\pi\int^{b}_{a} [f(x)-k]^2dx$  ile hesaplanır.
Özel olarak $y=f(x)$ fonksiyonunun grafiği ile x-ekseni arasında kalan bölgenin $y=0$ etrafında döndürülmesi oluşan özel cismin hacmi $V=\pi\int^{b}_{a} [f(x)]^2dx$ ile bulunur.

###### Örnek 1: 
$f(x)=\sqrt{9-x^2}$ eğrisinin $[-3,3]$ aralığında sınırladığı bölgenin $y=0$ doğrusu etrafında döndürülmesi ile elde edilen cismin hacmi nedir?
###### Çözüm 1:
$V=\pi\int^{3}_{-3} [f(x)]^2dx=\pi\int^{3}_{-3} (9-x^2)dx=\pi(9x-\frac{x^3}{3})|_{-3}^{3}=((27-9)-(-27+9))=36\pi$ $br^3$.

###### Örnek 2:
$[2,5]$ aralığında $f(x)=\frac{x}{4}$ ile x-ekseni arasında kalan bölgenin x-ekseni etrafında döndürülmesi ile elde edilen cismin hacmi nedir?
###### Çözüm 2:
$V=\pi\int_{2}^{5}(\frac{x}{4})dx=\frac{\pi}{4}(\int_{2}^{5}xdx)=\frac{\pi}{8}(x^2)|_2^5=\pi\frac{(25-4)}{8}=\frac{21\pi}{8}$ $br^3$.

###### Örnek 3:
$[2,5]$ aralığında $f(x)=\frac{1}{4x}$ ile x-ekseni arasında kalan bölgenin $y=-1$ etrafında döndürülmesi ile elde edilen cismin hacmi nedir?
###### Çözüm 3:
Bu örnek okuyucuya alıştırma olarak bırakılmıştır.

###### Örnek 4:
$f(x)=\sqrt x +2$ eğrisinin $[0,4]$ aralığındaki yayının $y=2$ doğrusu etrafında döndürülmesiyle oluşan dönen cismin hacmini bulunuz?
###### Çözüm 4:
$V=\pi\int_0^4 (\sqrt x + 2 - 2)^2dx=\pi\int_0^4 xdx=\frac{\pi}{2}(x^2|_0^4)=8\pi$ $br^3$.

$[a,b]$ aralığında sürekli $f(x)$ ve $g(x)$ fonksiyonlarının grafikleri arasında kalan bölgenin x-ekseni etrafında döndürülmesiyle oluşan dönen cismin hacmi $V=\pi\int_a^b |{f(x)}^2-{g(x)}^2|dx$ ile hesaplanır.

###### Örnek 5:
$f(x)=x^2$ ve $g(x)=\sqrt x$ fonsiyonları arasında kalan bölgenin x-ekseni etrafında döndürülmesi ile oluşan cismin hacmini bulunuz.
###### Çözüm 5:
$x^2=\sqrt x$ çözülerek fonksiyonların kesiştiği noktalar $(0,0)$ ve $(1,1)$ bulunur.
$V=\pi\int_0^1 |(x^2)^2-(\sqrt x)^2|dx=\pi\int_0^1 |(x^4-x|dx=\pi\int_0^1 (x-x^4)dx=\frac{3\pi}{10}$ $br^3$.

###### Örnek 6:
$[0,3]$ aralığında $f(x)=e^x$ ve $g(x)=2x+1$ fonksiyonlarının grafiklerinin arasında kalan bölgenin $y=0$ etrafında döndürülmesi ile oluşan cismin hacmini bulunuz.
###### Çözüm 6:
Verilen aralıkta $g(x)>f(x)$ olduğu için mutlak değer kaldırılabilir.
$V=\pi\int_0^3 e^{2x}-(2x+1)^2dx=\pi\int_0^3 (e^{2x}-4x^2-4x-1)dx=\pi[\frac{e^6-1}{2}-57]$ $br^3$.

### Silindirik Kalıp Yöntemi