# mikroprocesorski_sistemi
STM &amp; Proteus

Projektni zadatak:

Potrebno je realizovati paljenje i gasenje led diode tako da:

1. Ako Vase ime i prezime sadrzi veci broj samoglasnika od suglasnika, izabrati port A,
   ako Vase ime i prezime sadrzi veci broj suglasnika od samoglasnika, izabrati port B,
   inace izabrati port C.
2. Broj slova u Vasem imenu i prezimenu po modulu 6 daje broj odgovarajuceg pina, na prethodno izabranom portu.
3. Led dioda treba biti ukljucena onoliko milisekundi koliko ima slova u Vasem imenu, u daljem tekstu vreme_on.
4. Led dioda treba biti iskljucena onoliko milisekundi koliko ima slova u Vasem prezimenu, u daljem tekstu vreme_off.
5. Vreme_on i vreme_off se naizmenicno smenjuju nakon jednog ciklusa.

------------------------------------------------------------------------------------------------------------------------------

ime_prezime = PetarJovic:
broj_suglasnika = 6
broj_samoglasnika = 4

broj_suglasnika > broj_samoglasnika:
port = B

ime_prezime mod 6:
pin = 4

ime_duzina = 5:
vreme_on = 5 (mS)

prezime_duzina = 5:
vreme_off = 5 (mS)
