## Tanım
$S$ bir küme ve $*$ S üzerinde bir [[İkili İşlem]]dir. Aşağıdaki 3 koşul sağlanırsa $<A, *>$ [[Cebirsel Yapı]]sı bir gruptur.
1. $<A,*>$ [[İkili İşlem#Birleşme Özelliği]]ne sahiptir.
2. $<A,*>$ [[İkili İşlem#Birim Özdeşlik Etkisiz Eleman]]a sahiptir.
3. $<A,*>$ [[İkili İşlem#Ters Eleman]]a sahiptir.

**Dikkat:** Grup tanımında [[İkili İşlem#Kural 2 Kapalılık]] şartı tekrardan verilmemiştir. Çünkü bu şart $S$ üzerinde ikili işlem tanımlanmasının bir sonucudur.

### Yarı Grup
Yalnızca [[Cebirsel Yapı#Özellik 2 Kapalılık]] özelliğini ve [[İkili İşlem#Birleşme Özelliği]]ni sağlayan [[Cebirsel Yapı]] **yarı grup** olarak adlandırılır.

### Değişmeli (Abel) Grup
Grup tanımına ek olarak [[İkili İşlem#Değişme Özelliği]] sağlanıyorsa [[Cebirsel Yapı]] **değişmeli (abel) grup** olarak adlandırılır.

### Sonlu ve Sonsuz Grup
Grupların üzerine kurulduğu kümelerin eleman sayısı grubun *mertebesini* belirler. Sonlu kümeler üzerine kurulan gruplara *sonlu mertebeli gruplar*; sonsuz kümeler üzerine kurulan gruplara da *sonsuz mertebeli gruplar* denir.

## Örnekler
#### Örnek 1:
$<\mathbb{Z}, +>$ bir grup mudur?

- $a,b,c\in \mathbb{Z}$ alınsın. $a+(b+c) = (a+b)+c$ olduğu açıktır. G1 sağlanır.
- $a+e=a; e+a=a \Rightarrow e=0$ şeklinde birim elemanın varlığı bulunacaktır. G2 sağlanır. 
- $a+a^{-1}=0 \Rightarrow a^{-1}=-a$ (1)
   $a^{-1}+a=0\Rightarrow a^{-1}=-a$ (2)
  (1) ve (2)'nin tüm $\mathbb{Z}$ kümesini taradığı ve her elemanın tersini bulduğu açıktır. G3 sağlanır.
$\therefore <\mathbb{Z}, +>$ bir gruptur.

#### Örnek 2:
$<\mathbb{Z},*>$ bir grup mudur?

- $a,b,c\in\mathbb{Z}$ alınsın. $a*(b*c)=(a*b)*c$ olduğu açıktır. G1 sağlanır.
- $a*e=a; e*a=a \Rightarrow e = 1$ şeklinde birim elemanın varlığı bulunur. G2 sağlanır.
- $a*a^{-1}=1\Rightarrow a^{-1}=\frac{1}{a}\notin\mathbb{Z}$ olduğundan ters eleman yoktur. Aynı durum soldan da geçerli olacaktır.
$\therefore <\mathbb{Z}, *>$ bir grup değildir.

#### Örnek 3:
$\mathbb{N}$ üzerinde \* ikili işlemi $a*b=a+b$ olarak veriliyor. $<N,*>$ bir grup mudur?

- $a,b,c\in\mathbb{N}$ alınsın. $a*(b*c)=a*(b+c)=a+b+c=(a+b)+c=(a*b)+c=(a*b)*c$ olduğu görülecektir. G1 sağlanır.
- $a*e=a\Rightarrow e+a=a; e*a=a\Rightarrow e+a=a\therefore e=0$ biçiminde birim eleman tespit edilir. G2 sağlanır.
- $a*a^{-1}=0\Rightarrow a^{-1}=-a$ (1)
   $a^{-1}*a=0\Rightarrow a^{-1}=-a$ (2)
   $a=1$ için $a^{-1}=-1\notin\mathbb{N}$ dolayısıyla her elemanın tersi yoktur. G3 sağlanmaz.
$\therefore<\mathbb{N},*>$ bir grup değildir.