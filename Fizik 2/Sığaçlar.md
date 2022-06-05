## Tanım
Biri +q ve diğeri -q ile yüklenmiş iki parçacığı uzayda aralarında d uzaklığı olacak biçimde yerleştirelim. Bu parçacıklar arasında oluşan elektrik alan çizgilerini çizelim. İşte bu sisteme **sığaç (kondansatör, kapasitör)** denir.

![[Pasted image 20220531135402.png]]

![[Pasted image 20220531140049.png]]
İki ucu arası potansiyel fark $V_{ab}=V_a-V_b$ olan bir sığacın sahip olduğu yük miktarı $Q$ ve sığa değeri $C$ ile verilsin. Aralarında 
- $V_{ab}\cdot C=Q$ bağıntısı bulunur.
- Dolayısıyla *sığanın birimi* **Coulomb/Volt** olan **Farad**'dır.

### Paralel Plakalı Sığaçlar
Aralarındaki mesafe $d$, plakaların yüzey alanı $A$, iki uç arası potansiyel fark $V_{ab}$ ve birisi $+q$ diğeri $-q$ yüklü iki paralel iletken levhaların arasındaki elektrik alanı Gauss Yasasını kullanarak hesaplayabiliriz. $E=\frac{\sigma}{\varepsilon_0}$ şeklinde ifade edilir. Burada sigma, yüzey yük yoğunluğunu ifade eder ve yük düzgün dağıldıysa $\frac QA$ olur. Düzgün elektrik alan ile potansiyel fark arasında da $E=\frac {V_{ab}}d$ bağıntısı vardır. İki bağıntı beraber yazılıp düzenlendiğinde
$\frac{Q}{A\varepsilon_0}=\frac{V_{ab}}d$
$\Rightarrow\frac{Q}{V_{ab}}=\frac{A\varepsilon_0}{d}$ 
$\Rightarrow C=\varepsilon_0\cdot\frac{A}{d}$.

### Sığaçta Depo Edilen Enerji
 ![[Pasted image 20220531143544.png]]
 Herhangi bir $dq$ parçacığını, $V_{ab}$ potansiyelinde hareket ettirmek için yapılan iş $dW$'dir.
 $dW=dq\cdot V_{ab}=dq\cdot\frac qC$ şeklinde yazılabilir. Burada $C$ sığacın sığasıdır.
 Bu sığacın tamamen dolması için gerekli olan iş $W$'yi hesaplamak için her tarafın integralini alırız. Sığacın boş olduğundan ve tamamen dolacağı durumu hesaplamak istediğimizden sınırları $0$'dan $Q$'ya olacak şekilde seçeceğiz.
 $W=\int_0^Q dq\cdot \frac qC$. $\frac 1C$ sabit olduğundan dolayı öne atılır
 $=\frac 1C\int_0^Q qdq$
 $=\frac 1C\cdot(\frac 12\cdot[q^2|_0^Q])$
 $=\frac{Q^2}{2C}$. 
 - $Q=C\cdot V_{ab}$ bağıntısı kullanılarak $W=\frac 12 CV_{ab}^2$ veya $W=\frac 12 QV_{ab}$ şeklinde de ifade edilebilir.

### Enerji Yoğunluğu
Sığaçlarda enerji elektrik alanda depo edilir. Paralel plakalı sığaçlardan yararlanarak birim hacimdeki enerji yoğunluğunu hesaplayabiliriz.
![[Pasted image 20220531145008.png]]
Sığacın hacmi $V=Ad$ olarak gösterilebilir ve sığaçta depo edilen enerji $U=\frac 12 CV^2$ olarak hesaplanmıştı.
Böylece enerji yoğunluğu $u=\frac{1/2 CV^2}{Ad}$
$=1/2 \frac{Ad^{-1}\varepsilon_0(Ed)^2}{Ad}$
$=\frac 12 \varepsilon_0 E^2$ olur. Birimi **Joule/metreküp**'tür.

### Sığaçların Bağlanması
#### Seri Bağlanma
![[Pasted image 20220531150957.png]]
$V_{ab}=V_1+V_2$
$Q=Q_1=Q_2$
Bağlı sığaçların arasında kalan bölgede **net yük daima sıfır**dır.
Bağlı sığaçların yükleri birbirine eşit ve $Q$ kadardır çünkü sisteme yük girmemekte ve yük çıkmamaktadır.
Eş değer sığacın sığası $C_{eş}$'i hesaplamak için $Q=CV$ bağıntısından yararlanalım. $\frac Q{C_{eş}}=V_{ab}=V_1+V_2$
$=\frac{Q_1}{C_1}+\frac{Q_2}{C_2}$ 
$\Rightarrow\frac 1{C_{eş}}=\frac 1{C_1}+\frac 1{C_2}$. 
#### Paralel Bağlanma
![[Pasted image 20220531152619.png]]
$V_{ab}=V_1=V_2$ (1)
$Q_1=V_1C_1$ ve $Q_2=V_2C_2$.
$C_{eş}V_{ab}=C_1V_1+C_2V_2$. Her tarafı sadeleştiririz (bağıntı 1)
$C_{eş}=C_1+C_2$

### Sığaçlar ve Yalıtkanlar (Dielektrikler) Arasındaki İlişki
1. Levhalar arası boş
![[Pasted image 20220531153434.png]]
Levhalar arası boşluk olan sığacın sığası $C_0=\varepsilon_0\frac Ad$ olarak hesaplanır.

2. Levhaların arasında dielektrik madde var
![[Pasted image 20220531153646.png]]
Sığacın sığası dielektrik maddenin sabiti $k$ kadar artar. $C=kC_{eş}$. ($k>1$ )

Dielektrik madde içermeyen sığacın levhaları arasında oluşan elektrik alan $\overrightarrow{E_0}=\frac{V_0}d$ olacaktır. 
![[Pasted image 20220531190012.png]]
Dielektrik madde içeren sığacın içinde indüklenmiş olan parçacıklardan dolayı, oluşan elektrik alana ters bir $\overrightarrow{E_{ind.}}$ alanı oluşur.
![[Pasted image 20220531190759.png]]
Bu durumdaki sığaçta elektrik alan $E=E_0-E_{ind.}$ ve bu değer de $E=\frac{E_0}k$ olur. $k$'nin dielektrik maddenin dielektrik sabiti olduğunu unutmayalım.
Bu bağıntıdan hareketle levhalar arasındaki fark için de $V=\frac{V_0}k$ yazılabilir.