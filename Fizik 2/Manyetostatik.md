## Giriş
Yüklü parçacıklara etkiyen [Manyetik Kuvvet](Manyetik%20Kuvvet.md)lerin meydana getirdiği olayları, zamandan bağımsız [Manyetik Alan](Manyetik%20Alan.md)ları inceleyen manyetostatik konu başlığı altında
1. Sabit Manyetik Alanda Dairesel Hareket
2. Akım Taşıyan Tele Etkiyen Manyetik Kuvvet
3. Sabit Manyetik Alanda Yüklü Parçacığın Enerjisi
4. Akım Taşıyan İlmeğe Etkiyen Manyetik Kuvvet
altbaşlıklarını ele alacağız.

## 1. Dairesel Hareket
Manyetik alana giren yüklü parçacığın üzerine etkiyen kuvvet, hem manyetik alan hem de hız vektörüne diktir. Bundan dolayı da parçacığın ivmesi manyetik alana dik bir düzlem üzerinde meydana gelir. Bu ivme sonucunda parçacık düzgün dairesel hareket yapar.
![](Pasted%20image%2020220605190649.png)
![](Pasted%20image%2020220605191026.png)
$F_{man.}=F=qvB\sin\theta$ olduğunu biliyoruz. $\theta=0$ olacak. $a_{mer.}$ merkezcil ivme $\frac {v^2}R$, $F_{mer.}=mv^2R^{-1}$. $F_{man.}=F_{mer.}$ olacağından $R$ yarıçap ve $T$ hareketin periyodunu türetebiliriz.

$qvB=mv^2R^{-1}$ düzenlenirse $R=\frac{mv}{qB}$ olduğu bulunur. Hareketin yarıçapı $v$ parçacık hızı ile doğru, $B$ manyetik alan şiddeti ile ters orantılıdır. Aşağıdaki diyagramda da bu durum açıkça görülmektedir: 
![](Pasted%20image%2020220605193009.png)

Dairesel hareketin periyodu $T=\frac{2\pi R}v$ bağıntısıyla verilir. $R$ için elde ettiğimiz bağıntıyı yerine koyarak $T=\frac{2\pi m}{qB}$ olduğunu gösterebiliriz.
## 2. Tele Etkiyen Kuvvet
Akım taşıyan bir telin herhangi bir parçasını izole ederek başlayacağız. Bu sonsuz küçüklükteki tel parçasının uzunluğu $dl$, $dt$ süre içinde geçen yükler $dq$ olacaktır. Bu kabuller üzerine yüklerin hızı $\overrightarrow v=\frac{\overrightarrow dl}{dt}$ olduğunu söyleyebiliriz.

Aldığımız tel parçası sonsuz küçüklükte olduğundan üzerine etkiyen $B$ manyetik alanı *düzgün* olacaktır. Böylece tel parçasına etkiyen $\overrightarrow dF$ kuvvetini $\overrightarrow dF=dq\cdot v\times B$
$=dq\cdot\frac{d\overrightarrow l}{dt}\times \overrightarrow B$, bu noktada $I=\frac{dq}{dt}\Rightarrow dq=Idt$ yer değiştirmesiyle
$dF=IdlB\sin\theta$ olacaktır. Vektörel açılımı yapmasaydık aynı denklem $\overrightarrow dF=I\cdot\overrightarrow dl\times\overrightarrow B$ biçiminde yazılacaktı.

Elimizdeki sonsuz küçük tel parçasından yola çıkarak (uzunluğunu bildiğimiz) sonlu bir tel parçasının üzerine etkiyen kuvveti tespit etmek için bulduğumuz bağıntının iki tarafının da integralini alacağız.
$F_{man.}=I\int_a^b(\overrightarrow dl\times\overrightarrow B)$ manyetik alana yerleştirilen herhangi bir tel parçasının a noktasından b noktasına dek etkiyen manyetik alan kuvvetini verir. Biz bu integrali çözmek için içinden $I$ akımı geçen, manyetik alana dik yerleştirilmiş, $L$ uzunluğundaki teli ele alacağız. Bahsettiğimiz tel $(+y)$ ekseni üzerinde yer almakta, manyetik alan $(+x)$'e dik biçimde konumlandırılmış.
![](Pasted%20image%2020220605195940.png)
Her küçük tel parçasına etkiyen kuvvet $\overrightarrow dF=I[(dl\cdot\hat j)\times(B\hat i)]$
$=IBdl(\hat j\times\hat i)$
$=IBdl\cdot(-\hat k)$ olur. Bu ifadenin integralini aldığımızda
$\int\overrightarrow dF=(IB\int_0^L dl)\cdot(-\hat k)$ 
$=IBL\cdot(-\hat k)$ olarak bulunur.

Aşağıdaki kısa formül yukarıda yaptığımız işlemlerle aynı sonucu verecektir.
> $\overrightarrow F=IBL\sin\theta\cdot\hat k$
