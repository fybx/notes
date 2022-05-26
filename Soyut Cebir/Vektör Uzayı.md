## Tanım
$<K,+,\cdot>$ bir [[Cisim]], $V$ üzerinde $*:V\times V\mapsto V$ [[İkili İşlem]]i ve $\circ:K\times V\mapsto V$ [[Dış İşlem]]i tanımlanmış bir küme olsun.  Aşağıdaki aksiyomlar sağlanıyorsa *$V$'ye $K$ üzerinde [[Vektör]] uzayı* denir:
1. $\forall a,b,c\in V$ için $a*(b*c)=(a*b)*c$  ([[İkili İşlem#Birleşme Özelliği]])
2. $\forall x\in V$ için $x*e=x=e*x$ olacak şekilde $\exists e\in V$ vardır.  ([[İkili İşlem#Birim Özdeşlik Etkisiz Eleman]])
3. $\forall x\in V$ için $x*x^{-1}=e=x^{-1}*x$ olacak şekilde $\exists x\in V$ vardır.  ([[İkili İşlem#Ters Eleman]])
4. $\forall x,y\in V$ için $x*y=y*x$ eşitliği geçerlidir. ([[İkili İşlem#Değişme Özelliği]])
5. $\forall a\in K$ ve $\forall x,y\in V$ için $a\circ(x*y)=(a\circ x)*(a\circ y)$
6. $\forall a,b\in K$ ve  $\forall x\in V$ için $(a*b)\circ x=(a\circ x)*(b\circ x)$
7. $\forall a,b\in K$ ve  $\forall x\in V$ için $(a\circ b)\circ c=a\circ(b\circ c)$
8. $\forall x\in V$ için $e\circ x=x$ olacak şekilde $\exists e\in K$ vardır.

- İlk 4 şartın $V$ kümesinin [[Grup#Değişmeli Abel Grup]] olduğunu buldurduğuna dikkat et.

- $\mathbb{R}^2$, $\mathbb{R}^3$ birer vektör uzayıdır.