## Tanım
- $S\neq\emptyset$
- $x,y\in S$
- $f: S \times S \mapsto S$
- $\Rightarrow$ $(x, y) \longmapsto f(x, y) = x * y$

S kümesi boştan farklı herhangi bir kümedir. S'den x ve y elemanları seçilsin. f fonksiyonu S'nin kendisiyle kartezyen çarpımından kendine tanımlanan bir fonksiyondur. 

Satır 5'te verilen işlemde **ikili işlem**, * işareti ile gösterilir. İkili işleme **iç işlem** de denir. ^446d2a

#### Kural 1: Tekillik  
> $S \neq \emptyset$,  $(S, *)$ bir cebirsel yapı olmak üzere $a, b \in S$ alınıyor

$a * b = c$ ifadesinde $c$, $(a, b)$ sıralı ikilisine özel olmalıdır. (c bir tek sayı olmalıdır) S'nin her bir sıralı ikilisine tam olarak bir eleman karşılık getirilir.

#### Kural 2: Kapalılık
> $S \neq \emptyset,$  $(S, *)$ bir cebirsel yapı olmak üzere

$S \times S \longmapsto S$ sağlanmalıdır. Yani $a, b \in S \Rightarrow a * b \in S$ olmalıdır.

Bu ikili işlem ve ikili işlemin tanımlandığı S kümesi beraber bir **[[Cebirsel Yapı]]** meydana getirir. Bu yapı,

> $(S, *)$

biçiminde gösterilir.

## İnsancıl Tanım
> İkili işlem özel tanımlı bir fonksiyondur. Girdiler $S \times S$ kümesinin elemanları (sıralı ikilileri), çıktılarsa $S$ kümesinin elemanlarıdır.

## Örnekler
Tamsayılar kümesinde tanımlı toplama, çıkarma, çarpma işlemi birer ikili işlemdir. (**Dikkat: bölme işlemi tamsayılar kümesinde bir ikili işlem değildir. **)

- $(2, 3) \longmapsto 2 * 3 = 2+3 \in \mathbb{Z}$
- $(3, -5) \longmapsto 3-(-5)=8\in \mathbb{Z}$

Doğal sayılar kümesinde çıkarma işlemi ikili işlem değildir:
$(1, 3) \longmapsto 1-3=-2\notin\mathbb{N}$

$\mathbb{N}$ üzerinde tanımlı bir * işlemi
> x * y = x + y + 2xy olarak veriliyor

Buna göre 1 * 4 ve 2 * 0 nedir?

1 * 4 = 1 + 4 + 2 * 1 * 4 = 13
2 * 0 = 2 + 0 + 2 * 2 * 0 = 2

## İkili İşlem Tabloları

![[IMG_ikiliislemtablosu.jpg]]
Tablonun sol kolonunda yer alan elemanlar, işlem işaretinin solunda yer alır. Tablonun üst satırında yer alan elemanlar, işlem işaretinin sağında yer alır.

## İkili İşlemin Özellikleri
### Değişme Özelliği
$\forall x,y\in S \Rightarrow x * y = y * x$ denkliği sağlanıyorsa **değişme özelliği** vardır.

Tamsayılar kümesi üzerinde 
- toplama işlemi **değişmelidir**.
- çıkarma işlemi değişmeli değildir.
- çarpma işlemi **değişmelidir**.

Örnek: $\mathbb{N}$ üzerinde tanımlı ikili işlemler $\oplus$ ve $\odot$

1. $a \oplus b = 2a + 3b - 2$
2. $x \odot y = x + y + 3xy$ 

Birincisiyi sınayalım, $a \oplus b = b \oplus a \Rightarrow 2a + 3b - 2 = 2b + 3a - 2$  tüm $(a, b)$ sıralı ikilileri için sağlanmaz.

İkinci de yukarıdaki gibi tekrardan yazıldığında katsayılar aynı olacağından eşitliğin iki tarafı da tıpatıp aynı olacaktır $\therefore \odot$ ikili işlemi değişmelidir. 

#### Tablo üzerinde gösterim

> Sol üst köşeden sağ alt köşeye çizgi çekilerek tablo incelendiğinde simetrik elemanlar aynı ise ikili işlem **değişmelidir**.

![[IMG_degisimozelligi.jpg]]
Yukarıdaki kurala göre Tablo 1'e bakıldığında * işleminin değişmeli olduğu görülür. Tablo 2'deyse işlem değişmeli değildir.

### Birleşme Özelliği
$\forall a,b,c \Rightarrow (a \odot b) \odot c = a \odot (b \odot c)$ eşitliği sağlanıyorsa, *parantezlerin yer değiştirmesi işlem sonucuna etki etmiyorsa*, ikili işlemde **birleşme özelliği vardır**.

Tamsayılar kümesi üzerinde
- toplama işlemi **birleşmelidir**.
- çıkarma işlemi birleşmeli değildir.
- çarpma işlemi **birleşmelidir**.

$\mathbb{R}$ üzerinde tanımlı ikili işlemler $\oplus$ ve $\odot$

1. $x \odot y = x + y + xy$
2. $a \oplus b = \frac{a-b}{3}$

Birinciyi çözümleyelim. 
$c \odot (b \odot v) = c \odot (b + v + bv) = c + b + v + bv + cb + cv + cbv$
$(c \odot b) \odot v = (c + b + cb) \odot v = c + b + cb + v + cv + bv + cbv$
İki eşitlik de birbirine eşittir $\therefore$ 1. öncüldeki $\odot$ ikili işlemi birleşme özelliği taşır.

İkinciyi çözümleyelim.
$c \oplus (b \oplus v) = c \oplus (\frac{b-v}{3}) = \frac{c - \frac{b-v}{3}}{3} = \frac{3c-b+v}{9}$
$(c \oplus b) \oplus v = (\frac{c-b}{3}) \oplus v = \frac{\frac{c-b}{3}-v}{3} = \frac{3c-b-v}{9}$
İki eşitlik birbirine eşit değildir, dolayısıyla $\oplus$ ikili işlemi birleşme özelliği taşımaz.

### Birim (Özdeşlik, Etkisiz) Eleman
$S$ kümesi üzerinde tanımlı * ikili işlemi var. Eğer $\forall x \in S$ için $e*x=x$ ve $x*e=x$ olacak biçimde bir $e \in S$ varsa ikili işlemin **birim elemanı** vardır. Her işlemin birim elemanı olmak zorunda değildir.

![[IMG_birimeleman.jpg]]

Reel sayılar (ve altkümeleri) üzerinde toplama için 0 birim elemandır. Çarpma için 1 birim elemandır.

Not: **Her ikili işlem için varsa birim eleman bir tanedir.**

###### Örnek: 
Tamsayılar kümesi üzerinde * işlemi
$a * b = a + b + 3$
olarak tanımlanıyor. Buna göre * işleminin birim elemanını tespit ediniz.

Sağdan $x * e = x + e + 3 = x \Rightarrow e = -3$
Soldan $e * x = e + x + 3 = x \Rightarrow e = -3$
Hem sağdan hem de soldan birim eleman -3 olarak bulunur.

###### Örnek:
Rasyonel sayılar üzerinde tanımlı * ikili işlemi
$a*b=2a+2b+2ab+1$
olarak tanımlanıyor. Birim elemanı varsa tespit ediniz.

Sağdan $x * e = 2x + 2e + 2xe + 1 = x$ çözüldüğünde $e = -\frac{1}{2}$
Soldan $e * x = 2e + 2x + 2ex + 1 = x$ çözüldüğünde $e = -\frac{1}{2}$
Hem sağdan hem de soldan birim eleman $-\frac{1}{2}$ olarak bulunur.
 
### Ters Eleman
$S$ kümesi üzerinde tanımlı bir * işlemi var. $x \in S$ olmak üzere $S$ kümesinin * işlemine göre birim elemanı varsa ters eleman $x^{-1}$ biçiminde gösterilir. $x^{-1} * x = e$ ve $x * x^{-1} = e$ denklemleri sağlanmalıdır.

$\mathbb{R}$ kümesinde toplama işleminin birim elemanı 0'dır.
2 + x = 0 (1)
x + 2 = 0 (2)
(1) ve (2)'den görüleceği üzere 2'nin toplama işlemine göre tersi -2'dir.

$\mathbb{R}$ kümesinde çarpma işleminin 0 için tersi yoktur.

###### Örnek:
Tamsayılar kümesinde tanımlı * ikili işlemi
$a * b = a + b - 2$ olarak veriliyor. 5'in tersi var mıdır?

Öncelikle birim eleman araştırılır.
$x*e=x \Rightarrow x + e -2=x \Rightarrow e = 2$
$e*x=x\Rightarrow e+x-2=x \Rightarrow e =2$
$e=2$ tespit edilir.

$x^{-1}*x=2 \Rightarrow x^{-1}+5-2=2\Rightarrow x^{-1}=-1$
$x*x^{-1}=2 \Rightarrow 5 + x^{-1}-2=2\Rightarrow x^{-1}=-1$
$5^{-1}=-1$p