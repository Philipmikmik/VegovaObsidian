# Kazalo
1. [[#Definicija]]
2. [[#Fotoefekt]]
	1. [[#Hertz]]
	2. [[#Fotocelica]]
3. [[#Rentgenska svetloba]]
---
# Definicija
- **Dualizem**
	- *EMV* (valovanje)
	- *fotoni* (delčna narava) -> energijski delci/svetlobni kvanti
- **Hitrost svetlobe** -> $c=3*10^8\frac{m}{s}=\nu*\lambda$
	- $\nu$ -> *frekvenca* \[$Hz$]
	- $\lambda$ -> *valovna dolžina* \[$m$]
- **Energija fotona** -> $W_{f}=h*\nu$
	- $h$ -> *planckova konstanta* ($6.63*10^{-34} Js$)
---
# Fotoefekt
### Hertz
- *Fotoefekt izbijanje elektronov s pomočjo svetlobe*
- **Energija fotona** -> $W_{f}=A_{i}+W_{k}$
	- $A_i$ -> *izstopno delo*
	- $W_k$ -> *kinetična energija* $e^{-}$ ($\frac{m*v^2}{2}$)
![[Fotoefekt 2024-04-10 17.26.52.excalidraw|100%]]
### Fotocelica
$$W_{k_{max}}=e_{0}*U_{0}$$
 ![[Fotoefekt 2024-04-10 17.46.18.excalidraw]]
---
# Rentgenska svetloba
$$W_{k_{max}}=W_{f}=h*\nu_{max}=\frac{h*c}{\lambda_{min}}$$
- $\lambda : 1pm - 10pm$
- $\lambda_{min}=\frac{h*c}{e_{0}*U}$
![[Svetloba 2024-04-10 18.12.26.excalidraw]]
![[Svetloba 2024-04-10 18.18.31.excalidraw|100%]]

---
# Radioaktivnost
$$N_{(t)}=N_{0}*e^{-\lambda t}$$
- $N_{0}$ -> *začetno št. jeder*
- $\lambda$ -> *razpadna konstanta* $=\frac{\ln 2}{t_{1/2}}$
- $t_{1/2}$ -> *razpolovni čas*
- **Povprečen življenski čas** -> $T=\frac{1}{\lambda}$
```functionplot
---
title: 
xLabel: t
yLabel: N
bounds: [0,5,0,5]
disableZoom: true
grid: true
---
f(x)=(1/(x)^2)
```
