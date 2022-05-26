## Tanım
Yönlü doğru parçasına **vektör** denir ve genellikle $u, v...$ gibi küçük harflerle gösterilirler.

Başlangıç noktası A, bitim noktası B olan ve belli bir uzunluğa sahip olan vektör $\overrightarrow{AB}$ olarak gösterilir. A = B ise vektörün uzunluğu sıfırdır, bu vektör özel olarak **sıfır vektörü** ismini alır.

Doğrultuları ve yönleri eşit vektörlere *eşit vektör* denir. Herhangi bir vektör $u$'nun tersi $-u$ şeklinde gösterilir.

### Skaler ile çarpım
$0\neq u$ herhangi bir vektör ve $k\in\mathbb{R}$ alınıyor.

$ku$:
- $k>0$ ise $k$ tane $u$'nun toplamı
- $k=0$ ise $0$
- $k<0$ ise $k$ tane $-u$'nun toplamı
biçiminde tanımlanır.

### Vektör farkı
$u$ vektörü ile toplandığında $v$ vektörünü veren $w$ vektörüne *$u$ ile $v$ vektörlerinin farkı* denir ve $w=u-v$ ile gösterilir.

### Gösterim
$u$ $\mathbb{R}^2$ düzleminde bir vektör, $u$ vektörünün bitim noktası $(u_1,u_2)$ koordinatları, $u$ vektörünün *bileşenleri* olarak adlandırılır. Böylelikle $u$ vektörü *$u=(u_1,u_2)$* olarak yazılır.

Bundan hareketle $\mathbb{R}^3$ uzayındaki bir $u$ vektörünün $(u_1,u_2,u_3)$ biçiminde gösterileceği anlaşılır.

### Yer Vektörü
$A$ herhangi bir noktadır. Başlangıç noktası orijin olan $\overrightarrow{0A}$ vektörüne $A$ noktasının *yer vektörü* denir.

### Norm (Modül)
Bir $u$ vektörünün uzunluğuna $u$'nun *normu (modülü)* denir ve $\lVert u\rVert$ ile gösterilir.
- $\mathbb{R}^2$'de $\lVert u\rVert=\sqrt{{u_1}^2+{{u_2}^2}}$ olur.
- $\mathbb{R}^3$'te $\lVert u\rVert=\sqrt{{u_1}^2+{{u_2}^2+{{u_3}^2}}}$

### Birim Vektör
Uzunluğu 1 birim olan vektöre *birim vektör* denir. $u\neq0$ herhangi bir vektör olmak üzere $v=\frac{1}{\Vert u\Vert}u$ vektörü, $u$ vektörünün doğrultu ve yönündeki birim vektörüdür.

### Standart Birim Vektörler
$\mathbb{R}^2$ düzleminde x ve y eksenlerinin pozitif yönlerinde alınan, başlangıç noktası orijin olan $i=\hat{\imath}=(1,0)$ ve $j=\hat{\jmath}=(0,1)$ vektörleri *standart birim vektör*dür.

$\mathbb{R}^3$ uzayında $\hat{\imath}=(1,0,0)$ ve $\hat{\jmath}=(0,1,0)$ vektörlerine ek olarak bir de z ekseninin $k=\hat{k}=(0,0,1)$ vektörü vardır.

### Öklid İç Çarpım (Nokta Çarpım)
$u\cdot v$ :
- $u\neq0$ ve $v\neq0$ ise $\Vert u\Vert\Vert v\Vert\cos\theta$ 
- $u=0$ veya $v=0$ ise $0$
olarak tanımlanır.

İki vektörün nokta çarpımı bir skalerdir.
$u$ ve $v$ vektörleri için $u\cdot v=0$ oluyorsa $u$ ve $v$ vektörlerine *ortagonal (dik) vektörler* denir ve bu durum $u\bot v$ ile gösterilir.

### Vektörel Çarpım
$\mathbb{R}^2$ düzleminde bu işlem tanımlı değildir. $\mathbb{R}^3$ uzayında iki vektöre dik olan yeni bir vektör bulduran işlem *vektörel çarpım*dır.

$u=(u_1,u_2,u_3)$ ve $v=(v_1,v_2,v_3)$ herhangi iki vektör olmak üzere $u\times v=(u_2v_3-u_3v_2, u_3v_1-u_1v_3, u_1v_2-u_2v_1)$ şeklinde $u$ ve $v$ vektörlerinin vektörel çarpımı tanımlanır.

1. $u\cdot(u\times v)=0$, $v\cdot(u\times v)=0$
2. ${\Vert u\times v\Vert}^2={\Vert u\Vert}^2+{\Vert v\Vert}^2-{(u\cdot v)}^2$ (Lagrance Özdeşliği)
3. $u\times(v\times w)=(u\cdot w)v-(u\cdot v)w$
4. $(u\times v)\times w=(u\cdot w)v-(v\cdot w)u$

### $\mathbb{R}^n$'de Vektörler
$\forall u\in\mathbb{R}^n$ vektörü $u=(u_1,u_2,...,u_n)$ biçiminde gösterilir. Bundan hareketle *sıfır vektörü*nün $0=(0,0,...,0)$ olduğu görülmelidir. Çok boyutlu vektörlerde de diğer vektör özelliklerinin tamamı geçerlidir.

$u,v\in\mathbb{R}^n$ ortogonal vektörler ($u\bot v$) olmak üzere $\Vert u\Vert=\Vert v\Vert=1$ ise $u$ ve $v$ vektörlerine *ortonormal vektör*ler denir.