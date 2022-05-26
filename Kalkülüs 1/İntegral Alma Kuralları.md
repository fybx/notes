## İntegral Alma Kuralları

###### Sabit sayıların integralinin yanına integrant gelir.
- $\int 3dx = 3x +c$
- $\int-2dy=-2y + c$
- $\int\frac{-1}{5}da=\frac{-1}{5}a+c$
- 
###### $x^ndx$ formunda olanlar
- $\int x^ndx=\frac{x^{n+1}}{n+1}+c$
- $\int xdx = \frac{x^2}{2}+c$
- $\int y^{-5}dy=-\frac{y^{-4}}{4}+c$

###### Yardımcı Kurallar
1. $\int af(x)dx=a\int f(x)dx$
2. $\int [f(x)\pm g(x)]dx=\int f(x)dx\pm\int g(x)dx$ 
3. $\int(ax+b)^ndx=\int\frac{(ax+b)^{n+1}}{a\cdot(n+1)}$ 

###### e'nin üssü birinci derece ise kural uygulanır
- $\int e^{ax+b}dx=\frac{e^{ax+b}}{a}+c$
- $e^xdx=e^x+c$
- $\int2e^{5x}dx=2\cdot\frac{e^{5x}}{5}+c$

###### $a>0$ ve $a\neq0$, üs birinci derece ise uygulanır
- $\int a^{mx+n}dx=\frac{a^{mx+n}}{m\cdot lna}+c$

###### İntegral sonucu ln çıkanlar
$\int\frac{c}{ax+b}dx$ formundaki integrallerin sonucu $ln$'li bir ifade olur.
- $\int\frac{1}{x}dx=ln|x|+c$
- $\int\frac{1}{x+a}dx=ln|x+a|+c$
- $\int\frac{1}{ax+b}dx=\frac{ln|ax+b|}{a}+c$ 

###### Trigonometrik İntegral Kuralları
1. $\int\sin(ax+b)dx=-\frac{\cos(ax+b)}{a}+c$
2. $\int\cos(ax+b)dx=\frac{\sin(ax+b)}{a}+c$
3. $\int[1+\tan^2(ax-b)]dx=\int\sec^2(ax+b)dx=\int\frac{1}{\cos^2(ax+b)}dx=\frac{\tan(ax+b)}{a}+c$ 
4. $\int[1+\cot^2(ax-b)]dx=\int\csc^2(ax+b)dx=\int\frac{1}{\sin^2(ax+b)}dx=-\frac{\cot(ax+b)}{a}+c$
5. $\int\tan(ax+b)dx=-\frac{\ln|\cos(ax+b)|}{a}+c$ 
6. $\int\cot(ax+b)dx=\frac{\ln|\sin(ax+b)|}{a}+c$ 
7. $\int\sec xdx=\ln|\sec x+\tan x|+c$ 
8. $\int\csc xdx=-\ln|\csc x+\cot x|+c$

###### Ters Trigonometrik Fonksiyon Çıkan İntegraller
1. $\int\frac{1}{1+(ax+b)^2}dx=\frac{\arctan(ax+b)}{a}+c$
2. $\int\frac{1}{\sqrt{1-(ax+b)^2}}dx=\frac{\arcsin(ax+b)}{a}+c$