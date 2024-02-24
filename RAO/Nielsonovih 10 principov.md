1.  **Prilagodi se realnemu svetu**
	- Uporabljaj splošne besede, ne tehnični žargon
	- Dovoli okrajšave in sinonime v ukaznih jezikih (alias)
	- Metafore so koristne, a lahko zavedejo (niso vedno razumljive)
		- Razbremenjujemo obremenitev uporabnikovega spomina
		- So hitro naučljive, če so primerne (npr. namizje, mapa, datoteke)
2. **Konsistentnost in standardi**
	- Princip najmanjšega presenečenja
		- Podobne stvari naj izgledajo in se obnašajo podobno
		- Različne stvari naj izgledajo različno
	- Druge lastnosti
		- Velikost, položaj, brava, besede (pojasnila, terminologija)
	- Vrstni red ukazov in argumentov
		- Prefiksna ali postfiksna notacija
	- Upoštevaj navodila platform
	- Konsistentnost omogoča uporabnikom, da prenesejo svoje obstoječe znanje z lahkoto na nov vmesnik
	- Vrste konsistentnosti
		- Notranja (znotraj dane aplikacije)
		- Zunanja (znotraj platforme npr. Kako je z menuji pri drugih?)
		- Metaforična (v primerjavi z objekti realnega sveta)
	- Upoštevaj navodila platform
		- Java Look / Feel Design Guidelines
		- Apple Human Interface Guidelines
		- Windows Vista User Experience Guidelines
3. **Pomoč in dokumentacija**
	- Uporabniki ne berejo priročnikov
		- Izboljšaj vmesnik v smeri njigovih opravil, ne pa da jih učiš svojega sistema
	- Priročniki in takojšnja pomoč sta kljub temu nujna
		- Običajno, ko je uporavnik frustriran ali v krizi
		- Uporabnik išče konkretne odgovore
	- Pomoč mora omogočati:
		- Lahko preiskovanje
		- Usmerjena k opisu nalog
		- Konkretna
		- Kratka
4. **Uporabnikov nadzor in svoboda**
	- Dobro označeni izhodi – uporabnik naj ne bo ujetnik
	- Vsi dialogi morajo imeti gumb Cancel
	- Zagotovi razveljavitev akcije (Undo)
	- Zagotovi nadzor nad podatki
	- Dolge operacije naj bodo prekinjene
	- Omogoči urejevanje vnesenih podatkov s strani uporabnika
5.  **Vidljivost statusa sistema**
	-  Iluzija napredka – uporabnik mora biti ves čas obveščen o statusu sistema
	- Tekoče spremembe
	- Povdarjanje in vidljivost izbora
	- Statusna vrstica
	- Vidljivost akcij, ukazov, načinov in stanja med navigacijo
	- Odzivni časi
		- < 0.1s: se zdi zvezno
		- 0.1 – 1s: uporabnik opazi, povratna informacija ni potrebna
		- 1 – 5s: kurzor naj spremeni obliko
		- > 5s: prikaži indikator napredka
6. **Fleksibilnost in učinkovitost**
	- Zagotovi lahko naučljive bližnjice za pogoste operacije
		- Bližnjice preko tipkovnice (mnemoniki, bližnjice)
		- Okrajšave ukazov (alias)
	- Zagotovi:
		- Privzete nastavitve
		- Zgodovino
		- Pričakovanja
7. **Izogibanje napakam**
	- Izbira je manj podvržena napakam od tipkanja
		- Ne pretiravajte
	- Onemogoči napačne (nemogoče pri dani akciji) ukaze
		- V menuju se ne prikaže Copy, če ni nič izbrano
	- Uporabljaj menuje in forme, ne ukazni jezik
	- Vse potrebne informacije naj bodo vidne
	- Zaščiti uporabnikovo delo (samodejni Save, Undo, različice datoteke)
8. **Raje prepoznaj kot si zapomni**
	- Uporabljaj menuje ne ukazni jezik
	- Uporabi kombinirane sezname, ne besedilna območja
	- Uporabljaj generične ukaze, kjer je to možno
		- Copy, Paste, Cut, Open
	- Vse potrebne informacije naj bodo vidne
9. **Javljanje napak, diagnoza, reševanje**
	- Bodi natačen, daj dobro obvestilo o napaki
		- File missing or wrong format (kateri format je pravi)
		- File can't be parsed (ime datoteke)
		- Line too long (katera vrstica)
		- Name contains bad characters (katere)
	- Skrivaj tehnične detajle, razen na željo
		- FileNotFoundException
		- 404 Page Not Found
	- Daj konstruktivno pomoč
		- Povej zakaj je prišlo do napake in kako jo odpraviti
	- Bodi prijazen in ne grajaj
10. **Estetika in minimalistično načrtovanje**
	- Manj je več, preprostost
		- Izogibaj se odvečni informaciji, grafikam, lastnostim
	- Gradniki naj imajo večkratno vlogo
	- Dobro grafično načrtuj
		- Uporabi le nekajdobro izbranih pisav, barv in detaljov (CGP)
	- Uporabljaj kratek in jedrnat jezik
		- Pazljivo izbiraj znake