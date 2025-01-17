- **Komunikacija človek - računalnik** -> disciplina, ki se ukvarja z načrtovanjem, vrednotenjem in implementacijo interaktivnih računalniških sistemov za človekovo uporabo in s študijami glavnih fenomenov, ki spremljajo te sisteme. 
- Ljudje za interakcijo z računalnikom uporabljajo uporabniški vmesnik
- Vmesnik je mesto kjer se srečujejo in delujejo neodvisni sistemi, ki med seboj lahko komunicirajo
- Uporabniški vmesnik je mesto, ki združuje vhodne in izhodne naprave, programsko opremo in te resurse uporablja:
	- Vhod omogoča uporabniku manipulacijo s sistemom
	- Izhod omogoča sistemu, da pokaže učinke uporabnikove manipulacije
# Vrste
- Konzolno usmerjeni uporabniški vmesniki (Akcija – Objekt):
	- CLI
	- Navadni tekstovni vmesniki
	- Konzolni interaktivni tekstovni vmesniki
- Grafično podprti up. Vmesniki (Objekt – Akcija):
	- Dogodkovni interaktivni vmesniki ([[X11]])
	- Dogodkovni interaktivni vmesniki z grafičnim uporabniškim vmesnikom (GUI)
		- Pišemo le kodo, ki pomeni odzive na dogodke
# Strukturne razlika
- Pri konzolnih vmesnikih programer aplikacije določa, kdaj bi prišlo do vnosa podatkov ali izpisa rezultatov. Govorimo o postopkovnem programiranju.
- Pri grafično podprtih UV lahko uporabnik izvaja akcije kadarkoli. Dogodkovno usmerjeno programiranje
	- So bolj intuitivni, zaporedja akcij ni mogoče vedeti v naprej
- <u>Navadni tekstovni vmesniki</u>
	- Niso interaktivni, linearno izvajanje, vnaprej določeno zaporedje ukazov
- <u>Konzolni interaktivni tekstovni vmesniki</u>
	- Vhodni ukazi uporabnika, nelinearno izvajanje
	- Program se ustavi, ko čaka na vnos uporabnika in se nato nadaljuje
	- Nepredvidljiv vrstni red akcij, veliko prostega časa (program čaka)
- <u>Dogodkovni interaktivni vmesniki</u>
	- Vhodni ukazi uporabnika, nelinearno izvajanje
	- Uporabnik v vsakem trenutku lahko dela različne stvari (tipka v tekstovno okno, poveča okno, ...)
	- Tem odzivom pravimo DOGODKI (events)
	- Nepredvidljiv vrsti red akcij, veliko prostega časa
	- Na dogodke čaka zanka dogodkov za katero poskrbi aplikacija sama
- **Vrste vhodnih dogodkov**
	- Preprosti vhodni dogodki (premik miške, pritisk ali spust tipke...)
	- Prevedeni vhodni dogodki (visokonivojski dogodki)