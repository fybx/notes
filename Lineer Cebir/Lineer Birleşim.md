## Tanım
Lineer Birleşim genellikle [[Vektör]]ler konusunda kullanılan bir kavramdır fakat yalnızca vektörlerde kullanılmaz. Tanımı vektörler üzerinde verdikten sonra genelleştireceğiz.

$V$, $K$ cismi üzerinde bir vektör uzayıdır. $v_1,v_2,...,v_n\in V$ vektörleri ve keyfi $c_i\in K$ skalarları ile oluşturulan $\sum_{i=1}^{n} c_iv_i$ vektörüne *$v_1,v_2,...,v_n$ vektörlerinin bir lineer birleşimi* denir.

### İnsancıl Tanım
> $v_1,v_2,v_3$ vektörleri alınıyor. Bu vektörlerin lineer birleşimi, herhangi bir sabit sayı ile çarpılıp toplanmalarıdır. $c_1,c_2,c_3\in\mathbb{R}$ için $c_1v_1+c_2v_2+c_3v_3$ bu vektörlerin lineer birleşimidir.

$v_1=(1,-1,4)$, $v_2=(2,0,-3)$, $v_3=(4,1,5)$ vektörleri verilsin. $2v_1+3v_2-v_3$ lineer birleşiminin oluşturduğu vektör $(4,-3,-6)$'dır.

###### Örnek 1:
$v_1=(2,1,-3)$, $v_2=(3,1,5)$, $v_3=(0,2,4)$ vektörleri veriliyor. $w=(3,-4,5)$ vektörünün $v_1$, $v_2$, $v_3$ vektörlerinin lineer birleşimi olduğunu gösteriniz.

$w=c_1v_1+c_2v_2+c_3v_3$ sağlayan $c_1,c_2,c_3$ sabit sayılarını göstermeliyiz. $c_1(2,1,-3)+c_2(3,1,5)+c_3(0,2,4)=(3,-4,5)\Rightarrow (2c_1,1c_1,-3c_1)+(3c_2,1c_2,5c_2)+(0c_3,2c_3,4c_3)=(3,-4,5)$ buradan $2c_1+3c_2=3$, $c_1+c_2+2c_3=-4$ ve $-3c_1+5c_2+4c_3=5$ denklemleri gelecek. Bu sistem [[Matris]] kullanarak veya yerine yazma yöntemi ile çözülebilir. $c_1=-\frac{10}{7}$, $c_2=\frac{41}{31}$, $c_3=-\frac{95}{42}$ bulunur. $w=-\frac{10}{7}v_1+\frac{41}{31}v_2-\frac{95}{42}v_3$ şeklinde lineer birleşim olduğu gösterilir.