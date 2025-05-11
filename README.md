Ukupan broj efektivnih linija:
- Calculator.java - 129
- Start.java - 19

** Ukupan LOC: 138

Pregled koda(bez pokretanja),zapazanja i potencijalni problemi:
-Fajl Calculator.java:


Statisticka analiza:

-Calculator.java - 42. linija - Ogranicenje -1 znaci da se poslednji karakter u stringu nece proveriti sto potencijalno dovodi do pogresne kalkulacije ili povratne vrednosti "ERROR"
-Calculator.java - 55. linija - Kod tretira "Infinity" kao validan broj u izrazu,ali korisnik verovatno nece rucno kucati "Infinity" u kalkulator pa ova provera može biti visak.
-Calculator.java - 88. linija - Nema potrebe za +=, jer je result već 0.
-Calculato.java - 107. linija - Nedostaje provera deljenja sa nulom.
-Calculator.java - 110.,122.,138.,149. linija - Ponavljanje koda uz male izmene matematickih operacija.

Zakljucak: Prisutna ponavljanja koda i tesko uvodjenje novih operanada bez vece izmene koda.Kompletnom kodu nedostaju komentari i tesko je citljiv bez istih.

-Fajl Start.java:

Statisticka analiza:

-Start.java - 12. linija - Definisanje Scanner objekta unutar pretlje
-Start.java - 15. linija - Nedostaje validacija unosa sa dodatnim objasnjem

Zakljucak: Pravilno postavljanje Scanner-a za unos korisnickog izraza, i da ptelja omogucava unos vise izraza. Takodje nedostaju kljucni komentari i ako je jednostavan kod za pokretanje aplikacije. 