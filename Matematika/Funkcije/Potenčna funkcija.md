# Kazalo
1. [[#Definicija]]
2. [[#Korenska funkcija]]
3. [[#Grafi]]
---
# Definicija
$$f(x)=x^{n} \space \lor \space f(x)=x^{-n}; \space n\in\Bbb{N}$$
- Tipi:
	- [[#Grafi#$x^2k$|$x^{2k}$]]
	- [[#Grafi#$x^{2k+1}$|$x^{2k+1}$]]
	- [[#Grafi#$x^{-2k}$|$x^{-2k}$]]
	- [[#Grafi#$x^{-2k+1}$|$x^{-2k+1}$]]
---
# Korenska funkcija
- Točka $T(x, y)$ v potenčni funkciji se preslika v $T(y, x)$ v korenski fun.
- Inverzna fun. potenčne
- Primer [[#Grafi#$ sqrt[3]{x}$]]
---
# Grafi
### $x^{2k}$
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
### $x^{2k+1}$
```functionplot
---
title: 
xLabel: x
yLabel: y
bounds: [-10,10,-10,10]
disableZoom: true
grid: true
---
f(x)=x^3
```
### $x^{-2k}$
```functionplot
---
title: 
xLabel: x
yLabel: y
bounds: [-10,10,-10,10]
disableZoom: true
grid: true
---
f(x)=x^-2
```
### $x^{-2k+1}$
```functionplot
---
title: 
xLabel: x
yLabel: y
bounds: [-10,10,-10,10]
disableZoom: true
grid: true
---
f(x)=x^-3
```
### $\sqrt[3]{x}$
> Inverzna $x^{3}$
> ***!Program neki ne dela, tud negativna števila se nariše!***
```functionplot
---
title: 
xLabel: x
yLabel: y
bounds: [-10,10,-10,10]
disableZoom: true
grid: true
---
f(x)=x^3
g(x)=pow(x, 1/3)
```
