# Fraktalna stabla – sekvencijalna i paralelna implementacija

## Opis problema
Fraktalna stabla predstavljaju grafički model zasnovan na rekurzivnom grananju, gde se iz jedne početne grane generišu nove grane pod određenim uglovima i sa smanjenom dužinom. Ovaj problem je pogodan za paralelizaciju jer se svaka grana može računati nezavisno od ostalih.

Cilj ovog projekta je generisanje fraktalnog stabla i analiza razlike između sekvencijalne i paralelne implementacije algoritma.

## Planirano rešenje
Problem će biti rešen korišćenjem programskog jezika **Python**.

Biće implementirane sledeće verzije:
- **Sekvencijalna verzija** algoritma za generisanje fraktalnog stabla
- **Paralelna verzija** algoritma korišćenjem `multiprocessing` biblioteke, gde se izračunavanje grana izvršava paralelno

## Način rada
Algoritam koristi rekurzivni pristup:
- Počinje se od početne grane definisane dužinom i uglom
- Svaka grana se deli na dve ili više novih grana
- Proces se ponavlja do zadate dubine rekurzije

Rezultat izvršavanja algoritma biće sačuvan u datoteci koja sadrži koordinate grana po iteracijama, što omogućava dalju obradu ili vizualizaciju.

## Cilj projekta
Cilj projekta je demonstracija:
- razlike u načinu izvršavanja sekvencijalnog i paralelnog algoritma
- osnovnih principa paralelnog programiranja
- primene paralelizacije na rekurzivne probleme
  
## Radi
  Damir Marusic SR30/2023
