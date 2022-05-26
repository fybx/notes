## Tanım
$F$ bir [[Cisim]] ve $a_{ij}\in F$, $1\leq i\leq m$, $1\leq j\leq n$ olmak üzere
$A_{m\times n}=\left[ {\begin{array}{cc}a_{11} & a_{12} & \dotsb & a_{1n} \\a_{21} & a_{22} & \dotsb &a_{2n}\\\vdots&\vdots&\ddots&\vdots\\a_{m1}&a_{m2}&\dotsb&a_{mn}\end{array} } \right]$
şeklindeki bir tablo *m satır ve n sütonlu bir matris* olarak adlandırılır. $a_{ij}$, A matrisinin i. satır ve j. sütununu göstermek üzere A matrisi $A=[a_{ij}]$ veya $A=(a_{ij})$ şeklinde gösterilir.

Matristeki satır sayısı *denklem sayısını*, sütun sayısı da *bilinmeyen sayısını* temsil eder. İncele: [[Matris#Örnek 1]]

Eğer $m=n$ ise A matrisi *n. mertebeden kare matris* olarak adlandırılır. $A=[a_{ij}]$ n. mertebeden bir kare matris iken $a_{ii}$, $i=1,2,\dotsb,n$ elemanlarına *köşegen elemanları* ve bu elemanların bulunduğu köşegene de *esas köşegen* denir.

Sadece bir satırdan oluşan matrise *satır matrisi*, sütundan oluşana ise *sütun matrisi* denir.

Elemanları bir $F$ cisminden alınan tüm $m\times n$ boyutlu matrislerin kümesi $F_{m\times n}$ ile gösterilir.

### Eşit Matris
$A$ ve $B$, $F_{m\times n}$ kümesinden iki matris seçilsin. Karşılıklı elemanlarının tamamı birbirine eşit ise bu matrislere *eşit matrisler* denir.  

### Matriste Toplama
Eşit mertebeden alınan iki matris $A$ ve $B$'nin toplamları, karşılıklı elemanlarının toplamı ile elde edilen matrise eşittir.

Matriste toplama işlemi $\forall A=[a_{ij}]$, $B=[b_{ij}]\in F_{m\times n}$ matrisler olmak üzere $+:F_{m\times n}\times F_{m\times n}\rightarrow F_{m\times n}: ([a_{ij}], [b_{ij}])\rightarrow[a_{ij}+b_{ij}]$ şeklinde tanımlanır.

### Skalerle Çarpma
$F$ cisminden seçilen bir skaler ile $F_{m\times n}$ kümesinden seçilen matrisin çarpımı, matrisin her elemanının skaler ile çarpılması sonucu elde edilen matrise eşittir.

Skalerle çarpım $F\times F_{m\times n}\rightarrow F_{m\times n}:(k,[a_{ij}])\rightarrow[ka_{ij}]$ şeklinde tanımlanır.

### Matriste Çarpma
Matriste çarpma $\forall A=[a_{ij}]\in F_{m\times r}$, $\forall B=[b_{ij}]\in F_{r\times n}$ ve $\forall C=[c_{ij}]\in F_{m\times n}$ olmak üzere $F_{m\times r}\times F_{r\times n}\rightarrow F_{m\times n}:([a_{ij}],[b_{ij}])\rightarrow[c_{ij}]$ şeklinde tanımlanır. Burada $c_{ij}=a_{i1}b_{1j}+a_{i2}b_{2j}+\dotsb+a_{ir}b_{rj}=\sum_{k=1}^{r} a_{ik}b_{kj}$ şeklindedir.

Tanımdan da görüleceği üzere iki matrisin çarpılabilmesi için ilk matrisin sütun sayısının, ikinci matrisin satır sayısına eşit olması gerekir.

### Matrisin Devriği (Transpoze)
$\forall A\in F_{m\times n}$ matrisinin satırları ile sütunlarının yer değiştirmesi ile elde edilen matrise *$A$'nın  transpozesi* denir ve elde edilen matris $A^T$ ile gösterilir.
$A=\left[ {\begin{array}{cc}x\\y\\z\\\end{array} } \right]\Rightarrow A^T=\left[ {\begin{array}{cc}x&y&z\\\end{array} } \right]$

1. $(A+B)^T=A^T+B^T$
2. $(A^T)^T=A$
3. $(kA)^T=kA^T$
4. $\forall A\in F_{m\times n}$ ve $\forall B\in F_{n\times r}$ olmak üzere $(AB)^T=B^TA^T$'dir. 

### Matrisin İzi
Herhangi bir n. mertebeden kare matris A, $\forall A=[a_{ij}]\in F_{n\times n}$ alınıyor. Bu matrisin esas köşegen elemanlarının toplamına *$A$'nın izi* denir ve $izA$ ile gösterilir.
$izA=\sum_{i=1}^{n} a_{ii}$ biçiminde gösterilir.

### Matrisin Kuvveti
$\forall A\in F_{n\times n}$ matrisinin kendisi ile $k$ defa çarpımına $A$ matrisinin *k. kuvveti* denir ve $A^k$ ile gösterilir.

### Matrisin Tersi
$\forall A\in F_{n\times n}$ matrisi seçiliyor. Eğer $AB=BA=I_n$ olacak şekilde bir $B\in F_{n\times n}$ matrisi varsa $B$ matrisine *$A$ matrisinin tersi* denir ve $B=A^{-1}$ ile gösterilir. Bu şekildeki bir $A$ matrisi *tekil olmayan (singüler olmayan, düzgün, tersinir, ters çevrilebilir) matris* olarak adlandırılır. Aksi durumda da *tekil (singüler...)* olarak adlandırılır.

- Tekil olmayan $n\times n$ matris $A$ ve $B$ ise $AB$ matrisi de tekil olmayan matristir ve $(AB)^{-1}=B^{-1}A^{-1}$'dir.
- $\forall A\in F_{n\times n}$ tekil olmayan matris ise $A^T$ de tekil olmayan matristir. 

## Özel Matrisler
### Köşegen Matris
$A=[a_{ij}]\in F_{n\times n}$ matrisinde her $i\neq j$ için $a_{ij}=0$ oluyorsa, yani $A$ matrisinin esas köşegen üzerindeki elemanları hariç tüm elemanları sıfırsa, $A$ matrisine *köşegen matris* denir.

### Skaler Matris
$A=[a_{ij}]\in F_{n\times n}$ matrisi bir köşegen matris olmak üzere $A$'nın esas köşegen elemanları aynı skalere eşit ise $A$ matrisine *skaler matris* denir.

### Birim Matris
$A$ bir skaler matris ve esas köşegen elemanları $1$ ise $A$ matrisine *n. dereceden birim matris* denir ve $I_n$ ile gösterilir.

### Üçgensel Matris
$A=[a_{ij}]\in F_{n\times n}$ matrisinde $i>j$ için $a_{ij}=0$ ise $A$ matrisine *üst üçgensel matris*, $j>i$ için $a_{ij}=0$ ise *alt üçgensel matris* denir.

### Simetrik Matris
$A=[a_{ij}]\in \mathbb{R}_{n\times n}$ matrisi seçiliyor. Eğer $A^T=A$ oluyorsa $A$ matrisine *simetrik matris* denir. Simetrik bir $A$ matrisi için $\forall i,j$ için $a_{ij}=a_{ji}$'dir.

Simetrik matrislerin çarpımının simetrik olması gerekmez. $A$ ve $B$ simetrik matrisler, $(AB)^T=B^TA^T=BA$ olacağından $AB=BA$ özelliği sağlanmıyorsa $AB$ çarpım matrisi simetrik değildir. Dolayısıyla *"İki simetrik matrisin çarpımının simetrik olması için gerek ve yeter şart A ve B matrislerinin değişmeli (komütatif) olmasıdır."* denir. 

### Ters Simetrik Matris
$A=[a_{ij}]\in \mathbb{R}_{n\times n}$ matrisi seçiliyor. Eğer $A^T=-A$ oluyorsa $A$ matrisine *ters simetrik matris* denir. 

### Ortagonal Matris
$A=[a_{ij}]\in \mathbb{R}_{n\times n}$ matrisi seçiliyor. Eğer $AA^T=A^TA=I_n$ oluyorsa $A$ matrisine *ortagonal matris* denir. 

## Örnekler
###### Örnek 1:
$3x-2y-5z=10$
$x+6y+z=8$
Denklem sistemi veriliyor. Matris biçiminde gösteriniz.
$\left[ {\begin{array}{cc}3&-2&-5\\1&6&1\\\end{array} } \right]\left[ {\begin{array}{cc}x\\y\\z\\\end{array} } \right]=\left[ {\begin{array}{cc}10\\8\\\end{array} } \right]$
3x2 matris ile 1x3 matrisin çarpımı sonucu 1x2 matris elde ediliyor. 