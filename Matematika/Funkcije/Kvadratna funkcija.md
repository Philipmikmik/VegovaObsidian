# Kazalo
1. [[#Definicija]]
2. [[#Oblika]]
3. [[#Diskriminanta]]
4. [[#Grafi]]
	1. [[#Primer]]
---
# Definicija
$$f(x)=a*x^{2}+b*x+c;\ a,b,c\in \Bbb{R};\ a\ne0$$
- **$a$** -> vodilni koeficient
- $c$ -> premik gor/dol
- Tipi: 
	- [[#Grafi#a > 0|$a > 0$]] 
	- [[#Grafi#a < 0 |$a < 0$]]
- ---
# Oblika
- $f(x)=a(x-p)^2+q$ -> temenska oblika
	- $p=-\frac{b}{2a}$
	- $q =-\frac{D}{4a}$
- $f(x)=a(x-x_{1})(x-x_{2})$ -> ničelna oblika
---
# Diskriminanta
$$D = b^{2}-4ac$$
- $D > 0$ -> dve rešitvi *(ničli)*
- $D = 0$ -> ena rešitev
- $D < 0$ -> ni rešitev *(kompleksna)*
---
# Grafi
### Primer
$f(x)=2x^{2}+5x-3$
```functionplot
---
title: 
xLabel: x
yLabel: y
bounds: [-10,10,-10,10]
disableZoom: true
grid: true
---
f(x)=2x^2+5x-3
```

### a > 0
```functionplot
---
title:
xLabel: x
yLabel: y
bounds: [-10,10,-10,10]
disableZoom: true
grid: true
---
f(x)=x^2
```
### a < 0
```functionplot
---
title: 
xLabel: x
yLabel: y
bounds: [-10,10,-10,10]
disableZoom: true
grid: true
---
f(x)=-x^2
```