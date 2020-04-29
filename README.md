**Napravite javne klase NizCelihBrojevaException, NizCelihBrojeva i WriteNizCelihBrojeva sa sledećim uslovima:**

a)	Klasa NizCelihBrojevaException predstavlja neproveravani izuzetak (nasleđuje klasu RuntimeException) i ima:
-	Javni konstruktor koji kao parametar prima poruku greške i poziva odgovarajući konstruktor nadklase prosleđujući mu parametar.

b)	Klasa NizCelihBrojeva koja ima: 
-	Atribut koji predstavlja niz celih brojeva. 
-	Atribut koji predstavlja brojač elemenata niza. Brojač na početku ima vrednost nula jer je niz prazan. 
-	Konstruktor u kome se niz kreira tako da mu maksimalni kapacitet bude jednak vrednosti koja se prosleđuje konstruktoru u obliku ulaznog argumenta. 
-	Metodu za dodavanje elemenata u niz. Ova metoda prima kao ulazni argument broj koji je potrebno dodati u niz. Pre nego što se izvrši dodavanje, proverava se da li je kapacitet prekoračen (da li je brojač dostigao maksimalni kapacitet niza). Ako je kapacitet prekoračen, baciti izuzetak klase NizCelihBrojevaException sa odgovarajućom porukom. Ako nije, broj se dodaje na prvo slobodno mesto u nizu. Ako je element dodat, potrebno je u okviru metode uvećati vrednost brojača za jedan. 
-	Metodu koja sabira vrednosti prvog i poslednjeg elementa niza i vraća rezultat. Ako je niz prazan, vraca se poruka o tome. 
-	Metodu koja sabira samo pozitivne elemente niza i vraća njihovu vrednost. 
-	Metodu koja množi samo negativne elemente niza i vraća njihov proizvod. 
-	Metodu koja vraća broj ponavljanja nekog broja u nizu. Broj se prosleđuje metodi u vidu ulaznog argumenta. 
-	Metoda koja vraca članove niza koji su parni brojevi. 

c)	Glavna klasa WriteNizCelihBrojeva koja kreira tri objekta klase NizCelihBrojeva: prvi kapaciteta 3 člana, drugi kapaciteta 5 članova, a treći kapaciteta 10 članova. U prvi niz je potrebno ubaciti elemente 1, -1 i 3 u drugi elemente 34 i 45 a u treći elemente 56, 67 i – 89. Koristeći klasu PrintWriter u tekstualni fajl “nizCelihBrojeva.txt” upisati zbir prvog i poslednjeg elementa prvog niza, a drugi i treci niz upisati u obrnutom redosledu.
