# Kazalo
1. [[#Definicija]]
2. [[#Funkcije]]
---
# Definicija
$$f: x \rightarrow f(x)$$
- *"Funkcija $f$ iz množice A v množico B je predpis, ki vsakemu elementu iz A predpiše natanko en element v B"*
- Zaloga vrednosti = $Z_{f}$
- Definicijsko območje = $D_{f}$ 
- Graf: $\Gamma=\{(x,y); y=f(x);x\in D_{f}\}$
---
# Računanje z funkcijami
## 1. Osnovno računanje
- $D_{f}=D_{g}=[a,b]$
- Seštevanje -> $(f+g)(x)=f(x)+g(x)$
- Odštevanje -> $(f-g)(x)=f(x)-g(x)$
- Množenje -> $(fg)(x)=f(x)*g(x)$
- Deljenje -> $(\frac{f}{g})(x)=\frac{f(x)}{g(x)};\space g(x)\ne0$
- Produkt z št. -> $(c*f)(x)=f(x)*c;\space c\in\Bbb{R}$
## 2. Sestavljanje funkcij 
$$(f\circ g)(x)=f(g(x))$$
- $Z_{g}=D_{f}$
![[Funkcija 2023-12-02 15.47.24.excalidraw]]
## 3. Pretrganost
- **Def.** -> *Funkcija je na intervalu $[a,b]$ zvezna, če
 je tam graf NEPRETRGANA KRIVULJA.*
	 -> *Točke x iz $D_{f}$, kjer je graf pretrgan se imenujejo TOČKE NEZVEZNOSTI.*
	 -> *Funkcija je ZVEZNA , če je njen graf neptretrgana krivulja*
 
---
# Limita funkcije
$$\lim_{x\rightarrow a}f(x)$$
- **Def**. -> *Če funkcija v točki $a$ ni zvezna ali ni definirana, potem je njena limita enaka vrednosti, kateri točijo vrednosti funkcije z leve in desne, ko se $x$ približuje $a$.*
- *Če je funkcija v točki $a$ zvezna potem je limita kar enaka funkcijski vrednosti v tej točki.*
### Računanje z limitami
- *Veljajo ko se nastopajoče limite obstajajo in so končne*
- **Klasično računanje**:
1. $\lim_{x\rightarrow a}(f(x)\pm g(x))=\lim_{x\rightarrow a}f(x)\pm \lim_{x\rightarrow a}g(x)$
2. $\lim_{x\rightarrow a}(f(x)* g(x))=\lim_{x\rightarrow a}f(x)* \lim_{x\rightarrow a}g(x)$
3. $\lim_{x\rightarrow a}(\frac{f(x)}{g(x)})=\frac{\lim_{x\rightarrow a}f(x)}{\lim_{x\rightarrow a}g(x)}; \ \lim g(x) \ne 0$
4. $\lim_{x\rightarrow a}(c*g(x))=c*\lim_{x\rightarrow a}g(x)$
- **Posebni primeri**:
1. $\lim_{x\to\infty}{\frac{1}{x}}=0\ ;\ \lim_{x\to\infty}{\frac{1}{x}}=0$
2. $\lim_{x\to\infty}{\frac{1}{x^{n}}}=0\ ; \ n>0$
---
# Funkcije
- [[Linearna funkcija]]
- [[Kvadratna funkcija]]
- [[Polinomi]]
- [[Potenčna funkcija]]
- [[Eksponentna funkcija]]