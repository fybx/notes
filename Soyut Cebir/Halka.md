## Tanım
$H=\emptyset$ bir küme, $\oplus$ ve $\odot$ da iki [[İkili İşlem]] olsun. Aşağıdaki kuralları sağlayan $<H,\oplus,\odot>$  [[Cebirsel Yapı]]sına **halka** denir.
1. $<H,\oplus>$ bir [[Grup#Değişmeli Abel Grup]]tur.
2. $\odot$ işlemi asosyatiftir. $\forall a,b,c\in H$ için $a\odot(b\odot c)=(a\odot b)\odot c$.
3. $\odot$ işlemi $\oplus$ işlemine sağdan ve soldan dağılmalıdır.
4. $\forall a,b,c\in H$ için $a\oplus(b\odot c)=(a\oplus b)\odot(a\oplus c)$ sol dağılma ve $(a\odot b)\oplus c= (a \oplus c)\odot(b \oplus c)$ sağ dağılma geçerlidir

### Halkanın Sıfırı
Halkanın 1. işlemine göre [[İkili İşlem#Birim Özdeşlik Etkisiz Eleman]]ına **halkanın sıfırı** denir. $0_{H}$ biçiminde gösterilir. Her halkanın sıfırı mecburen vardır. (H1 > G2)

### Halkanın Birimi
Halkanın 2. işlemine göre [[İkili İşlem#Birim Özdeşlik Etkisiz Eleman]]ına **halkanın birimi** denir ve $1_H$ ile gösterilir. *Her halkanın birimi olmayabilir*. bkz: [[Halka#Birimli Halka]]

### Değişmeli (Komütatif) Halka
$<H, \odot, \oplus>$ halkasında 2. işlem $\oplus$ değişmeli ise halka, **değişmeli halka** olarak adlandırılır.

### Birimli Halka
$<H, \odot, \oplus>$ halkasında 2. işlem $\oplus$ [[İkili İşlem#Birim Özdeşlik Etkisiz Eleman]]a sahipse halka, **birimli halka** olarak adlandırılır. Bir halkada, eğer varsa, yalnızca bir tane etkisiz eleman bulunabilir.

### Sıfır Bölenli Halka
$H$ bir halkadır. $0_H\neq a\in H$ için $a*b=0_H$ olacak şekilde $b\neq 0_H,\exists b\in H$ varsa $H$ halkasına **sıfır bölenli halka** denir. Eğer böyle bir $b$ yoksa **sıfır bölensiz halka** denir.

Yani $a*b=0_H$ iken a veya b'den en az biri $0_H$ ise $H$'ye sıfır bölensiz halka denir.

### Tamlık Bölgesi
Birimli, değişmeli ve sıfır bölensiz halkaya **tamlık bölgesi** denir. 

### Bölümlü Halka
$H\neq\emptyset$ kümesinin herhangi bir elemanının çarpmaya göre tersi varsa, bu elemana *birim* denir. Eğer $\forall0\neq x\in\mathbb{R}$ için $xx^{-1}=x^{-1}x=1$ olacak şekilde $\exists x^{-1}\in\mathbb{R}$ ise bu yapıya **bölümlü halka** ya da [[Cisim#Aykırı Cisim]] denir.

### Halka örnekleri
- $<\mathbb{Z},+,*>; <\mathbb{Q},+,*>, <\mathbb{R},+,*>, <\mathbb{C},+,*>$ birer halkadır.
- $n\in\mathbb{Z}^{+}$ belli bir sayı ve $\oplus$ ile $\odot$ n modülüne ($\mathbb{Z}_{n}$) göre toplama ve çarpma işlemlerini gösterir. $<\mathbb{Z}_{n},\oplus,\odot>$ bir halkadır. (Burada $\mathbb{Z}_{n}=\lbrace0, 1, 2, ..., n-1\rbrace$ olduğu bilinmelidir)
- $<\mathbb{Z}_6,+,*>$ halkası sıfır bölenlidir. Sıfır olmayan iki eleman seçelim ve çarpalım. $3*2=0=0_{\mathbb{Z}_6}$ olduğu görülür. Çarpanlar halkanın sıfırı değilken çarpım halkanın sıfırı olduğuna göre halka sıfır bölenlidir.
- $\mathbb{Z}$ bir bölümlü halka değildir  $\because5$'in çarpmaya göre tersi $\frac{1}{5}\notin\mathbb{Z}$. $\mathbb{Z}$'deki birimler yalnızca 1 ve -1'dir.
- $n\in\mathbb{Z}^+$ bir asal sayı değilse $\mathbb{Z}_n$ halkası bir bölümlü halka (dolayısıyla [[Cisim]]) değildir. Örneğin $\mathbb{Z}_4$ halkasında 2 birim değildir. Eğer $p$ bir asal sayı ise $\mathbb{Z}_p$ bir cisimdir ve $0$ hariç tüm elemanlar birimdir.

## Örnekler
###### Örnek 1:
$\forall a,b\in\mathbb{Z}$ için $a\oplus b=a+b+1$ ve $a\odot b=ab+a+b$ ise $<\mathbb{Z},\oplus,\odot>$ yapısının birimli ve değişmeli halka olduğunu gösteriniz.

i. Halkanın birinci işlemi $\oplus$ ile $\mathbb{Z}$ [[Grup#Değişmeli Abel Grup]] oluşturmalı
	1. $\forall a,b,c\in\mathbb{Z}$ için $a\oplus(b\oplus c) = a\oplus(b+c+1)=a+b+c+1+1=(a+b+1)+c+1=(a\oplus b)+c+1=(a\oplus b)\oplus c$
	2. $a\oplus e=a=a+e+1=a$ ve $e\oplus a=a=e+a+1$ için $e=-1\in\mathbb{Z}$ olduğundan birim eleman $-1$ bulunur.
	3.  $a\oplus a^{-1}=e=a+a^{-1}+1=-1$ ve $a^{-1}\oplus a=e=a^{-1}+a+1=-1$ için $a^{-1}=-a\in\mathbb{Z}$ olduğundan kümenin tüm elemanları için ters eleman bulunur.
	4. $a\oplus b=a+b+1=b+a+1=b\oplus a$ olduğundan değişmeli olduğu bulunur. 
ii. Halkanın ikinci işlemi $\odot$ $\mathbb{Z}$ kümesinde birleşmeli. 
	$\forall a,b,c\in\mathbb{Z}$ için 
	$a\odot(b\odot c)=a\odot(bc+b+c)=abc+ab+ac+a+bc+b+c$ (1)
	$(a\odot b)\odot c=(ab+a+b)\odot c=abc+ac+ab+ab+a+b+c$ (2)
	(1) = (2)
iii. Halkanın ikinci işlemi $\odot$, birinci işleme $\oplus$ soldan ve sağdan dağılmalı
	$\forall a,b,c\in\mathbb{Z}$ için
	$a\odot(b\oplus c)=a\odot(b+c+1)=ab+ac+a+a+b+c+1$ (1)
	$(b\oplus c)\odot a=(b+c+1)\odot a=ba+ca+a+b+c+1+a$ (2)
	(1) = (2)
Bu noktada $<\mathbb{Z},\oplus,\odot>$ yapısının halka olduğunu kanıtladık.
iv. Halka birimli ise ikinci işlemi $\odot$ [[İkili İşlem#Birim Özdeşlik Etkisiz Eleman]]a sahip olmalı
	$a\odot e=a=ae+a+e\Rightarrow(a+1)e=0\Rightarrow e=0\in\mathbb{Z}$  (1)
	$e\odot a=a=ea+e+a\Rightarrow(a+1)e=0\Rightarrow e=0\in\mathbb{Z}$ (2)
	(1) = (2) $\Rightarrow e=0$
v. Halka değişmeli ise ikinci işlemi $\odot$ [[İkili İşlem#Değişme Özelliği]]ne sahip olmalı
	$\forall a,b\in\mathbb{Z}$ için $a\odot b=ab+a+b=ba+b+a=b\odot a$.
$\therefore <\mathbb{Z},\oplus,\odot>$ birimli ve değişmeli bir halkadır.