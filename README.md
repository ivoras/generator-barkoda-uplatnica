# Generator barkoda za uplatnice

Jednostavno generiranje 2D barkoda za uplatnice prema stanardu HUB-a (https://www.hub.hr/hr/format-zapisa-pdf417-2d-bar-koda-prema-hub3-standardu) napravljeno u Javascriptu, uključujući IFRAME podršku za integraciju u razne web app.

Vrlo jednostavno omogućite svojim klijentima printanje ili skeniranje 2D barkoda kako bi lakše napravili uplatu na vaš račun!

Za opis korištenja, pogledajte https://ivoras.github.io/generator-barkoda-uplatnica/ . Ostatak ovog dokumenta
je bitan samo ako želite nešto razvijati.

Ovaj projekt se sastoji od library-a koji omogućuje jednostavno prikupljanje, provjeravanje i pretvaranje podataka u format spreman za prebacivanje u 2D barkod po [standardu definiranom od strane Hrvatske udruge banaka](http://www.hub.hr/sites/default/files/2dbc_0.pdf), te primjera korištenja njega u kombinaciji sa [drugim library-om](https://github.com/bkuzmic/pdf417-js) (PDF417-js, autor Boris Kuzmic) za generiranje samog 2D barkoda iz teksta u traženom formatu. Iz primjera se može vidjeti kako koristiti oba library-a, ali je jednostavno i vidjeti kako bi se koristio pojedinačni library ukoliko želite.

Sve je potpuno besplatno i slobodno se koristi u komercijalne svrhe jer je pod licencom LGPL.

**NAPOMENA**: Neke stvari još nisu implementirane u stranici za primjer korištenja (vidi poglavlje [Stvari koje još nisu implementirane](#stvari-koje-još-nisu-implementirane)).

# Stvari koje još nisu implementirane
* Dokumentacija
* Na stranici za primjer korištenja nije implementirano ispisivanje poruke o kakvoj se grešci radi (validacija)
* Na stranici za primjer korištenja nije implementirano dinamičko postavljanje maksimalne duljine polja
* Validacija poziva na broj u odnosu na označeni model plaćanja
* Validacija IBAN-a
