# Projekat na kursu Geometrijski algoritmi 

Pred Vama se nalazi demonstracija upotrebe alata GCLC za dokazivanje teorema. Zadatak je dokazati da zbir unutrasnjih 
uglova trougla iznosi 180 stepeni. Ideja je proci kroz ceo dokaz, te se stoga pokretanjem fajla *korak1-paralelne-prave.gcl* 
moze videti vizualizacija prvog koraka, tj. povlacenja paralelnih duzi kroz temena. Zatim demonstriramo pronalazenje
podudarnih uglova (pokretanjem animacije pod nazivom *korak2-podudarni-uglovi.gcl*). Ukoliko korisnik zeli da se uveri u verodostojnost
prikaza na proizvoljno odabranom trouglu, to moze uraditi pokretanjem datoteke *trougao-sa-nasumicnim-tackama.gcl* (koji, za razliku
od svojih prethodnika, generise samo odgovarajucu sliku). Sada, kada je vizuelno jasno sta se desava, mozemo krenuti u proces dokazivanja:
najpre se pokretanjem programa *identical-A1A3.gcl* i *identical-A2A4.gcl* mozemo uveriti da su uglovi A1AA2 i A3AA4 jednaki (isto vazi i 
za uglove B1BB2 i B3BB4 - ovaj zakljucak dobijen je na osnovu izvrsavanja programa *identical-B1B3.gcl* i *identical-B2B4.gcl*).
Analogno, na isti nacin dokazujemo i jednakost uglova A1AA2 i C1CC2 sa jedne i uglova B3BB4 I C3CC4 sa druge strane. Sada, na
osnovu svega dokazanog i na osnovu krajnje slike ovih animacija, mozemo zakljuciti da uglovi C1CC2, C2CC4 i C4CC3 u zbiru daju 
opruzen ugao, tj. ugao od 180 stepeni. Podaci o pojedinacnim koracima koji su preduzeti da bi se teoreme dokazale, mogu se naci u odgovarajucim
XML fajlovima.

# Autor: Andjela Damnjanovic 59/2019
