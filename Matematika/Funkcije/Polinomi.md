# Kazalo
1. [[#Definicija]]
2. [[#Oblike]]
3. [[#Operacije v množini polinomov]]
	1. [[#Seštevanje/odštevanje]]
	2. [[#Množenje]]
	3. [[#Deljenje]]
---
# Definicija
$$p(x)=a_{n}x^{n}+a_{n-1}x^{n-1}+...+a_{1}x+a_{0};n\in\Bbb{N};a\in\Bbb{R}$$
- $a$ -> koeficient
- $a_{n}x^{n}$ -> vodilni člen
- $a_{n}$ -> vodilni koef.
- $a_{0}$ -> prosti člen
---
# Oblike
- $p(x)=a_{n}(x-x_{1})(x-x_{2})...(x-x_{n})$ -> ničelna$(\Bbb{R})$
- $p(x)=a_{n}(x-x_{1})(x^{2}+bx_{1}+c_{1})(x^{2}+bx_{2}+c_{2})$ -> ničelna$(\Bbb{C})$
---
# Operacije v množini polinomov
- $p,q:\Bbb{R}\rightarrow\Bbb{R}$
	$p(x)=a_{n}x^{n}+...+a_{1}x+a_{0}$
	$q(x)=b_{m}x^{m}+...+b_{1}x+b_{0}$
### Seštevanje/odštevanje
- $(p+q)(x)=p(x)+q(x)$
- $(p-q)(x)=p(x)-q(x)$
- $st(p+q)\le max\{n,m\}$
### Množenje
- $(pq)(x)=p(x)*q(x)$
- $st(p*q)=n+m$
### Deljenje
%%WIP%%

---
# Grafi
### Primer
$f(x)=-2x^5+1.5x^3+0.3x^2-5x+4$
```functionplot
---
title: 
xLabel: x
yLabel: y
bounds: [-20,20,-20,20]
disableZoom: true
grid: true
---
f(x)=-2x^5+1.5x^3+0.3x^2-5x+4
```
