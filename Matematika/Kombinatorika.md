# Kazalo
1. [[#Definicija]]
2. [[#Osnovni izreki kombinatorike]]
	1. [[#Pravilo produkta]]
	2. [[#Pravilo vsote]]
3. [[#Permutacije in variacije]]
4. [[#Kombinacije]]
	1. [[#Binomski izrek]]
5. [[#Verjetnost]]
---
# Definicija
- *Preštevanje možnosti*
- $n=A+B+C+\dots$
- $m=A*B*C*\dots$
- Fakulteta -> $n!=n*(n-1)*(n-2)*\dots*1$
	- $0!=1$
---
# Osnovni izreki kombinatorike
### Pravilo produkta
$$N=n_{1}*n_{2}*\dots*n_k$$
- ***Proces odločanja poteka v fazah***
- Vsaka faza ima $n$ možnosti
- *Vsaka faza neodvisna od prejšnjih*
### Pravilo vsote
$$M=n_1+n_2+\dots+n_k$$
- **Seštevek možnosti iz vseh množic**
- *Izbori vseh množic nezdružljivi med seboj*
---
# Permutacije in variacije
- **Permutacije** -> $P_{n}^{r_{1},r_{2},r_{k}}=\frac{n!}{r_1!*r_2!*\dots*r_k!}$
- **Variacije** -> $V^r_n=\frac{n!}{(n-r)!}$
- $n$ -> število elementov
- $r$ -> število mest (*brez ponavljanja*)
- So razvrstitve $n$ elementov, ki so različni *(vrstni red)*
---

# Kombinacije

$$C_n^r=\frac{V_n^r}{r!}=\frac{n!}{(n-r)!*r!}={n\choose r}$$
- **Kombinacija je izbor $r$ elementov iz množice z $n$ elementi.**
- $n\choose r$ -> binomski zapis za kombinacije
### Binomski izrek
- $(a+b)$ -> binom
- $(a+b)^n$ -> potenca binoma
$(a+b)^{n}=a^{n}+{n\choose 1}a^{n-1}b+{n\choose 2}a^{n-2}b^{2}+\dots+{n\choose n-1}ab^{n-1}+b^{n}$
---
# Verjetnost
- **Poskus** -> *vsaka načrtna aktivnost, ki jih izvajamo pod enakimi pogoji v naprej določenih pravilih*
- **Dogodek** -> *pojav, ki se pri poskusu zgodi ali ne*
	- Slučajni -> *se lahko zgodi*
	- Gotovi -> *se vedno zgodi*
	- Nemogoč -> *se ne more zgoditi*
- **Izid** -> *nesestavljen dogodek, ki se lahko zgodi ali ne*
- $P(A)=\frac{želen\ izid}{vse\ možnosti}=\frac{m}{n}$