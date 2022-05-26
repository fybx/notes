## Tanım
$V$ bir [[Vektör Uzayı]] ve $\emptyset\neq S\subseteq V$ olsun. $S$ kümesinde kapsanan sonlu sayıda elemanın tüm [[Lineer Birleşim]]lerinin oluşturduğu $W$ [[Alt Uzay]]ına *$S$'in gerdiği* veya *ürettiği* alt uzay denir ve $Sp\lbrace S\rbrace$ ile gösterilir.

Bu durumda $S$ kümesine $W$ alt uzayının *germe* veya *üreteç kümesi* denir. $S=\lbrace c_1,c_2,c_3,...,c_n\rbrace$ olması halinde $Sp\lbrace S\rbrace$ alt uzayı $Sp\lbrace c_1,c_2,c_3,...,c_n\rbrace$ ile gösterilir.

Böylece *"$c_1,c_2,c_3,...,c_n\in V$ ve $W=Sp\lbrace c_1,c_2,c_3,...,c_n\rbrace$ iken $c_1,c_2,c_3,...,c_n$ vektörleri $W$ alt uzayını gerer veya üretir"* denir.

### İnsancıl Tanım
> Bir $V$ vektör uzayının bütün elemanları $v_1,v_2,...,v_n$ vektörlerinin lineer birleşimi olarak yazılabiliyorsa, bu vektörlerin oluşturduğu $S={v_1,v_2,...,v_n}$ kümesi $V$ vektör uzayını gerer.

## Örnekler:
###### Örnek 1:
$V=\mathbb{R}^3$ uzayını $S=\lbrace(1,2,-1),(3,1,4)\rbrace$ kümesi gerer mi?
Hayır. Üç boyutlu bir vektör uzayını geren bir üreteç kümesi en az üç vektör elemanı içermelidir.

###### Örnek 2:
$S=\lbrace(1,2),(-1,1)\rbrace$ kümesi $\mathbb{R}^2$ vektör uzayını gerer mi?
1. $\mathbb{R}^2\longrightarrow(a,b)\in\mathbb{R}^2$
2. $c_1\cdot(1,2)+c_2\cdot(-1,1)=(a,b)$  çözümünden $c_1-c_2=a$ ve $2c_1+c_2=b$ sistemi elde edilir. $c_1=\frac{a+b}{3}$ ve $c_2=\frac{b-2a}{3}$ olarak elde edilir. Bu katsayılar bulunabildiği için $S$ kümesi $\mathbb{R}^2$ vektör uzayını gerer.

###### Örnek 3:
$S=\lbrace(2,4),(-1,-2)\rbrace$ kümesi $\mathbb{R}^2$ vektör uzayını gerer mi?
1. $\mathbb{R}^2\longrightarrow(a,b)\in\mathbb{R}^2$
2. $c_1\cdot(2,4)+c_2\cdot(-1,-2)=(a,b)$ çözümünden $2a=b$ elde edilir. Yalnızca bu kurala uyan $(a,b)$ vektörlerinin üretilmesi mümkün olduğundan $\mathbb{R}^2$ uzayındaki tüm vektörler elde edilemez.
3. Ayrıca $S$ kümesinin vektörlerinin lineer bağımlı olduğu da görülmektedir ki bu da üreteç kümesi olmadığını gösterir.