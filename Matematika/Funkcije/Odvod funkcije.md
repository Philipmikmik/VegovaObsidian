# Kazalo
1. [[#Definicija]]
2. [[#Računanje z odvodi]]
	1. [[#Pravila]]
	2. [[#Odvodi nekaterih funkcij]]
3. [[#Iskanje kotov]]
	1. [[#Naklonski kot krivulje]]
	2. [[#Med dvema krivuljama]]
4. [[#Eksteremi]]
---
# Definicija
$$f'(x)= \lim_{h\rightarrow 0}\frac{f(x+h)-f(x)}{h}$$
- **Odvod funkcije je enak limiti diferenčnega kvocienta, ko gre $h \rightarrow 0$**
- *Odvod funkcije v dani točki je enak $k$ (diferenčni kvocient) tangente/dotikalnice na grafu funkcije v tej točki.*
- $k=\frac{\Delta x}{\Delta y}=\frac{f(x+h)-f(x)}{h}$
- $f\parallel g \Rightarrow k_f=k_g$
- $f\perp g \Rightarrow k_{f}= -\frac{1}{k_g}$
---
# Računanje z odvodi
### Pravila
- $(f\pm g)'=f' \pm g'$
- $(f * g)' = f'*g + f*g'$
- $(\frac{f}{g})'=\frac{f'*g-f*g'}{g^{2}}$
- $(c*f)'=c*f'; c\in\mathbb{R}$
### Odvodi nekaterih funkcij
- $(x^n)'=n*x^{n-1}$
- $(c)' = 0$
- $(e^{x})'=e^{x}$
- $(a^{x})'=a^{x}*\ln{x}$
- $(\log_{a}{x})'=\frac{1}{x*\ln{a}}$
- $(\ln x)=\frac{1}{x}$
- $(\sin x)'=\cos x$
- $(\cos x)'=-\sin x$
- $(\tan x)'=\frac{1}{\cos^{2} x}$
- $(\cot x)'=\frac{-1}{\sin^{2} x}$
---
# Iskanje kotov
### Naklonski kot krivulje
$$\tan{\alpha}=\frac{\Delta y}{\Delta x}=k_t=f'(x_0)$$
- **Kot med krivuljo in x-osjo v ničli**
- $\alpha=\arctan k_t$ 
### Med dvema krivuljama
$$\tan\varphi=|\frac{k_1-k_2}{1+k_1*k_2}|$$
- **Če je imenovalec 0 je $\varphi=90^{ \circ }$**
---
# Eksteremi
- Def.: **Okolica točke je interval realnih števil okoli točke**
- *Funkcija $f$ ima v točki $x_{0}$ lokalni maksimum($M$)/minimum($m$), če obstaja okolica točke $x_0$, da je za vsak $x$ iz te okolice $f(x)\leq M$/$f(x)\geq m$*
- $x_{0} \Rightarrow f'(x)=0$ -> stacionarna točka
- $f'(x_{0})\gt0$ je lokalni minimum
- $f'(x_{0})\lt0$ je lokalni maksimum
- $f'(x_{0})=0$ je sedlo