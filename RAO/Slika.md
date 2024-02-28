# Vrste slik
- *Bitne* (rastrske slike) -> **.png, .gif, .jpg**
	-  2D tabela slikovnih elementov (pikslov)
	- Piksel je najmanjši element slike
		- Vsebuje zapis barve
	- Glede na slikovno globino ločimo
		- Črno-belo(1bit), sivinske(2bita), barvne(24bitov)
- *Vektorska* grafika (ta zmeraj dobro zgleda) -> **.svg, .ai**
	- Slika opisana z matematičnimi izrazi
		- Črte, krivulje, krog
	- Atributi
		- Stil, barva
# Zajem bitne slike
### <u>Kvantizacija</u>
- Pri pretvorbi analognega signala v digitalnega
	- Koliko vrednosti (bitov) imamo na voljo za zapis piksla
	- BPP (bits per pixel)
- Pri sliki je nivo kvantizacije enak barvni globini slike
	- 1bit = črno-bela slika
	- 2bita = sivinska slika
	- 24bitov = »True Color« (RGB)
### <u>Vzorčenje</u>
- Vzorčno svetlost/barvo na enakomerni 2D mreži
- Piksel je vrednost v točki, ne kvadrat
- Parameter vzorčenja je število pisklov
	- Če jih imamo premalo pride do prekrivanja
	- **Nyquistov zakon** (Sample rate mora biti dvakrat tolikšen kot največja frekvenca ki jo zajamemo signala, da se zmanjša možnost popačenja slike)