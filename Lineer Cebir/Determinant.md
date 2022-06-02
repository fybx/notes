## Tanım
Kare [[Matris]]lerde hesaplanan sabit bir değerdir. Determinantın sonucu bir sayıdır. Lineer denklem sistemlerinin çözülüp çözülemeyeceğini ve bir matrisin tersinin var olup olmadığını belirlemede  kullanılır.

$A$ matrisinin determinantı $detA$ ve $|A|$ ile gösterilir.

## Özellikler
1. Bir matriste tamamen 0'dan oluşan bir sütun bulunuyorsa o matrisin determinantı 0'dır.
2. Bir matriste bir satır veya sütün bir başka satır veya sütunun aynısı veya katı ise determinant sıfırdır. (Matrisin bazları tuttuğunu biliyoruz. Eğer iki tane baz [[Lineer Bağımlılık]] gösterirse matrisin ifade ettiği [[Lineer Dönüşüm]] vektör uzayının tamamını geremez)

## Determinant Hesabı
### 1x1 Matris
$1\times1$ boyutlu matrislerin determinantı kendisine eşittir.

### 2x2 Matris
$2\times2$ boyutlu matrislerin determinantı:
$A=\left[ {\begin{array}{cc}a&b\\c&d \end{array} } \right]$ ise $detA=ad-bc$  olarak hesaplanır.

### 3x3 Matris
![[Pasted image 20220602135323.png]]
Sarrus Yöntemi ile hesaplanır. $A=\left[ {\begin{array}{cc}a&b&c\\d&e&f\\g&h&j \end{array} } \right]$ ise $detA=aej+dhc+gbf-ceg-fha-jbd$ olarak hesaplanır.

### nxn Matris
Tüm matrislerin determinantının hesaplanmasında [[Kofaktör]]ler kullanılabilir. $n=4$ ve üstü için Sarrus Yöntemi gibi bir yöntem bulunmadığından kofaktörler kullanılmak zorundadır.

Örnek matrisimiz $A=\left[ {\begin{array}{cc}a&b&c\\d&e&f\\g&h&j \end{array} } \right]$ olacaktır.
1. Determinantı alınacak matrisin istenilen satırı veya sütunu seçilir. (içinde bol 0 olması önerilir)
Örnek için birinci satırı seçtik
2. Seçilen satır veya sütundaki her elemanla kendisinin kofaktörünün çarpımı toplanır. Sonuç matrisin determinantıdır.
$detA=a\cdot A_{11}+b\cdot A_{12}+c\cdot A_{13}$
$=a(ej-hf)+b(gf-dj)+c(dh-eg)$
$=aej-ahf+bgf-bdj+cdh-ceg$.