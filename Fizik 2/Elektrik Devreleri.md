## Tanım
![[Pasted image 20220531224101.png]]
Metallerin içerisinde serbest dolaşan elektronların rastgele hızları $V_r$ ile gösterilir ve yaklaşık olarak $4\times10^5 m/s$'dir. Rastgele hız, [[Akım]] konusunda ele alınan sürüklenme hızı $V_{sür.}$'den farklıdır. Sürüklenme hızı yaklaşık olarak $1mm/s$'dir.

Cismin iki ucu arasında potansiyel fark sıfıra eşit olduğunda, metalin içindeki elektronlar yalnızca rastgele hıza sahip olurlar. Sistemde akım olmaz, dolayısıyla sürüklenme hızından da bahsedilemez.

Bir devreden akım geçmesi için devrenin **kapalı devre** olması ve devrede **elektromotor kuvvet kaynağı** bulunması gerekir.
![[Pasted image 20220531224339.png]]
Yukarıdaki şekilde gösterilen pil hücresi bir elektromotor kuvvet kaynağıdır. İdeal bir bataryanın iki ucu arasında yarattığı potansiyel fark $V_{ab}$, bataryanın elektromotor kuvveti $\epsilon$'a eşittir.

## Kapalı Basit Devre
![[Pasted image 20220531225121.png]]
İdeal bir bataryaya bağlı, değeri $R$ olan direncin a ve b kolları arasındaki potansiyel fark $V_{ab}=\epsilon=IR$ olur. Eğer aynı devre *ideal olmayan* bir batarya ile kurulmuş olsaydı, bataryanın iç direnci söz konusu olurdu.

### İdeal Olmayan Bataryanın İç Direnci
![[Pasted image 20220531225634.png]]
İdeal olmayan bataryanın iç direncinden ötürü direnç üzerindeki potansiyel fark azalacaktır.
$V_{ac}$ bataryanın potansiyel farkı elektromotor kuvvet $\epsilon$ olduğu görülmektedir. $V_{bc}$ potansiyel farkının iç dirence, $V_{ab}$ potansiyel farkının da $R$ direncine ait olduğu görülmektedir. Öyleyse $V_{ac}=\epsilon=V_{ab}+V_{bc}$ olarak bir arada yazabiliriz. Buradan $\epsilon=IR+Ir$ geleceği açıktır.

Sonuç olarak iç direncin yarattığı kayıptan ötürü devrenin yükü olan $R$ direnci üzerindeki potansiyel fark, ideal bataryanın yarattığı elektromotor kuvvetten daha az olacaktır. Direncin kolları arası pot. fark $V_{ab}=\epsilon-Ir$ olduğu görülür.

İdeal olmayan batarya bulunan devrede akımı hesaplamak için de yukarıdaki bağıntıdan hareketle $I=\frac\epsilon{R+r}$ ve genelleştirildiğinde $I=\frac{\sum\epsilon}{\sum R}$ elde edilir.

## Ölçüm Aletleri
### Ampermetre
İç direnci çok küçüktür, üzerinden geçen akımı ölçerken kolları arasında potansiyel düşme yaratmaz. Devreye seri bağlanır.

### Voltmetre
İç direnci çok büyüktür, devreye paralel bağlanır. Voltmetrenin bağlı olduğu noktadan akım geçmez.

## Devre Elemanının Gücü
![[Pasted image 20220531230746.png]]
Yukarıdaki devrede verilen $dq$ yükünün potansiyel fark içerisinde yaptığı işi $dW=dq\Delta V$ bağıntısı ile hesaplıyorduk. Gücün tanımı da $P=\frac{dW}{dt}$, birim zamanda yapılan işti. $\frac{dW}{dt}=\frac{dq}{dt}\Delta V$ şeklinde yazılabilir. $I=\frac{dq}{dt}$ olduğundan $P=I\Delta V$ elde edilir. $\Delta V=V_{ab}$ olduğundan devrenin gücü $P=IV_{ab}$ olarak bulunur.

Gücün birimi **Joule/saniye** olan **Watt**tır.