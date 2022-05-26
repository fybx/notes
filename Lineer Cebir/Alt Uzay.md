## Tanım
$V\neq\emptyset$ bir [[Vektör Uzayı]]dır. $V$ kümesinin alt kümesi $W\neq\emptyset$ olsun. $V$ vektör uzayının [[İkili İşlem]]leri ve [[Dış İşlem]]leri $W$ kümesine indirgenmiş olsun. Eğer $W$ kümesi şu aksiyomları sağlıyorsa *alt uzay* olarak adlandırılır:
1. $w_1,w_2\in W$ için $w_1 + w_2\in W$ olmalıdır.
2. $w\in W$ ve $c\in R$ için $c\cdot w\in W$ olmalıdır.

- $\lbrace0\rbrace$ kümesi $V$ vektör uzayının alt uzayıdır.
- $V$ vektör uzayı kendisinin alt uzayıdır.
$\lbrace0\rbrace$ ve $V$ alt uzaylarına $V$'nin *aşikar alt uzayı*, geri kalan alt uzaylara da *has alt uzayı* denir. 
- Orijinden geçen her doğru $\mathbb{R}^2$ uzayının bir alt uzayıdır.

## Örnekler
###### Örnek 1:
 $W=\lbrace(x_1,x_2,x_3)\in\mathbb{R}^3|x_1=0\rbrace$ kümesi $\mathbb{R}^3$'ün bir alt uzayı mıdır?

1. $\forall a,b,c,d\in\mathbb{R}$ için $W_1=(0,a,b)$ ve $W_2=(0,c,d)$ seçilsin. $W_1+W_2=(0,a+b,c+d)\in\mathbb{R}^3$ olduğu açıktır.
2. $\forall x,a,b\in\mathbb{R}$ için $w=(0,a,b)\in W$ seçilsin. $c\cdot w=(c\cdot 0,c\cdot a,c\cdot b)=(0,ac,bc)\in\mathbb{R}^3$ olduğu açıktır. 
$\therefore W, \mathbb{R}^3$'ün bir alt uzayıdır.

###### Örnek 2:
$V=\lbrace(x_1,x_2,x_3)\in\mathbb{R}^3|x_1+x_2=2\rbrace$ kümesi $\mathbb{R}^3$'ün bir alt uzayı mıdır?

1. $V$ kümesinden seçilecek $V_1$ ve $V_2$ elemanlarının toplamı yine $V$ kümesinin bir elemanı olmalı. Öyleyse $V_1=(1,1,5)$ ve $V_2=(0,2,4)$ elemanlarını seçelim. $V_1+V_2=(1,3,9)\notin V$ olduğu açıkça görülmektedir. 
$\therefore V$ kümesi $\mathbb{R}^3$'ün bir alt uzayı olamaz.

###### Örnek 3:
$W=\lbrace(x,y,z)|x+2y=0\rbrace$ kümesi $\mathbb{R}^3$ vektör uzayının alt uzayı mıdır?

1. $W_1=(x_1,y_1,z_1)\in W\Rightarrow x_1+2y_1=0$ ve $W_2=(x_2,y_2,z_2)\in W\Rightarrow x_2+2y_2=0$ seçilsin. $W_1+W_2\in W$ olduğunu kontrol edeceğiz. $W_1+W_2=(x_1+x_2,y_1+y_2,z_1+z_2)\in W$ ise $(x_1+x_2)+2(y_1+y_2)=0$ sağlanmalıdır. $W_1$ ve $W_2$'yi seçerken elde ettiğimiz bağıntıları burada yerine koyarsak gerçekten de sağlandığını görürüz. Öyleyse $W_1+W_2\in W$'dır.
2. $\forall a\in\mathbb{R}$ ve $w=(x,y,z)\in W\Rightarrow x+2y=0$ seçilsin. $a\cdot w\in W$ olduğunu kontrol edeceğiz. $a\cdot w=(ax,ay,az)$ gerçekten de $W$'nin elemanı ise $ax+2ay=0$ eşitliği sağlanmalıdır. $x+2y=0$ olduğunu biliyoruz. Eşitliğin her iki tarafını $a$ ile çarparak $ax+2ay=0$ olduğunu gösterebiliriz. Öyleyse $a\cdot w\in W$'dır.

###### Örnek 4:
$W=\lbrace(x,y,z):x+2y=3\rbrace$ kümesi $\mathbb{R}^3$ kümesinin bir alt uzayı mıdır?

1. $W_1=(x_1,y_1,z_1)\in W\Rightarrow x_1+2y_1=3$ ve $W_2=(x_2,y_2,z_2)\in W\Rightarrow x_2+2y_2=3$ seçilsin. $W_1+W_2\in W$ ise $(x_1+x_2)+2(y_1+y_2)=3$ olmalıdır. Fakat 6 olarak bulunur. Demek ki $W_1+W_2\notin W$.
$\therefore W,\mathbb{R}^3$'ün bir alt uzayı değildir.

###### Örnek 5:
$1\leq m\leq n$ olsun. $\mathbb{R}^n$ kümesinin son $n-m$ tane elemanı $0$ olan tüm elemanlarının oluşturduğu $W$ kümesi $\mathbb{R}^n$ vektör uzayının bir alt uzayıdır. $0\in W$ yani $W\neq\emptyset$'dir.
1. $\forall X=(x_1,x_2,...,x_m,0,0,...,0)\in W$ ve $\forall Y=(y_1,y_2,...,y_m,0,0,...,0)\in W$ için $X+Y=(x_1+y_1,x_2+y_2,..., x_m+y_m,0,0,...,0)\in W$'dır.
2. $\forall c\in\mathbb{R}$ için $cX=(cx_1,cx_2,...,cx_m,0,0,...,0)\in W$'dır. 
$\therefore$ özel tanımlı $W$ kümesi gerçekten de $\mathbb{R}^n$ vektör uzayının bir alt uzayıdır.