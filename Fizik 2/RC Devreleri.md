## Sığacın Şarjı
![[Pasted image 20220605050915.png]]
Şekilde gördüğümüz devre bir RC (Resistor - Capacitor) devresidir. Devre anahtarı kapatıldığında elektromotor kuvvet etkisiyle hareket eden yükler kapasitörün şarj olmasını sağlar. Kapasitör şarj olduktan sonra devreden akım geçmez.

Bu olaydan iki denklem çıkaracağız. İlk denklem *zamana bağlı olarak devrede akan yükü* veren $q(t)$ fonksiyonunu elde etmemizi sağlayacak.

![[Pasted image 20220605051408.png]]
Anahtar kapatıldığında devreden geçen akımı Kirchhoff'un çevrim kuralına göre ele aldığımızda $\epsilon-\frac qC-I\cdot R=0$ elde edilecektir. Bunu düzenlerken $I=\frac{dq}{dt}$ ve $Q=CV$ olduğunu göz önünde bulunduralım: 
$\epsilon -\frac qC-\frac{dq}{dt}\cdot R=0$. Her iki tarafı $R$ değerine bölelim: 
$\frac\epsilon R-\frac q{RC}-\frac{dq}{dt}=0$. Aynı cins değişkenleri tek bir tarafta toplayalım: 
$\frac{dq}{dt}=\frac{C\epsilon-q}{RC}$. $dt$ ile $C\epsilon-q$ ifadelerinin yerini değiştirelim: 
$\frac{dq}{C\epsilon-q}=\frac{dt}{RC}$. Şimdi her iki tarafı integre edebiliriz. Sınırlarımızı belirleyelim, $t=0$ anında S anahtarını kapatacağız ve herhangi bir $t$ anına kadar bekleyeceğiz. Böylece $t$ süre içerisinde devreden geçen toplam yükü hesaplamış olacağız: 
$\int_0^q\frac{dq}{C\epsilon}=\int_0^t\frac{dt}{RC}$. Sol integralin üst sınırı $q$, sağ integralin üst sınırı $t$'dir çünkü $t$ sürede toplam yük $q$ kadar olacaktır. İntegraller çözüldüğünde aşağıdaki fonksiyon elde edilir:
> $q(t)=C\cdot\epsilon(1-e^{\frac{-t}{RC}})$

1. $t=0$ anında devreden geçen yük
    $q(0)=C\cdot\epsilon(1-1)=0$ olacağından ilk anda devreden akım geçmez.
2. $t\rightarrow\infty$, yani yeterli süre geçtiğinde devreden geçen yük
    $q_{son}=C\cdot\epsilon(1-\frac 1{e^\infty})$ parantezin içindeki ifadede $\frac 1{e^\infty}$ oldukça küçük olduğundan yok sayılır. Dolayısıyla $q_{son}=C\cdot\epsilon$ olacaktır.

![[Pasted image 20220605053024.png]]

Elimizdeki $q(t)$ fonksiyonunun türevini alarak *zamana bağlı olarak devreden geçen akımı* veren fonksiyonu elde ederiz. ($I=\frac{dq}{dt}$ olduğunu hatırla)

> $I(t)=\frac{dq(t)}{dt}=\frac\epsilon R\cdot e^{-\frac t{RC}}$ 

1. $t=0$ anında $I(0)=\frac\epsilon R\cdot e^0$ olacağından ilk anda devreden geçen akım $\frac\epsilon R$ yani **maksimum değerde** olacaktır.
2. $t\rightarrow\infty$ yani yeterince süre geçtiğinde $I_{son}=\frac\epsilon R\cdot e^{\frac{-\infty}{RC}}=0$ olacağından, *kapasitör şarj olduktan sonra* devreden akım geçmez.

![[Pasted image 20220605053716.png]]

## Zaman Sabiti
Olayı gözlemleyerek elde ettiğimiz $q(t)$ ve $I(t)$ fonksiyonlarındaki $RC$ ifadesi, sığacın **zaman sabiti**dir. Zaman sabiti, adı üstünde RC devresinin ne kadar sürede şarj olup ne kadar sürede deşarj olacağını hesaplamada kullanılır. Zaman sabiti $\tau=RC$ olarak gösterilir. $\varepsilon$      

## Sığacın Deşarjı
Biraz önceki devremizi şarj ettiğimizi, sığacın $t$ sürede $q$ yük biriktirdiğini ve artık devreden akım geçmediğini biliyoruz. Bu anda S anahtarını açarsak kapasitörde depolanan yük devreye geri verilecek, depolanan $q$ azalacak ve devreden başlangıçtakinin tersi yönde, *- işaretli*, akım geçecektir.