# Kata03.READMEKata03: How Big? How Fast?
Rough estimation is a useful talent to possess. As you’re coding away, you may suddenly need to work out approximately how big a data structure will be, or how fast some loop will run. The faster you can do this, the less the coding flow will be disturbed.

So this is a simple kata: a series of questions, each asking for a rough answer. Try to work each out in your head. I’ll post my answers (and how I got them) in a week or so.

## How Big?
- roughly how many binary digits (bit) are required for the unsigned representation of:

 - + 1,000
 + + 1,000,000
 + + 1,000,000,000
 + + 1,000,000,000,000
 + + 8,000,000,000,000
- My town has approximately 20,000 residences. How much space is required to store the names, addresses, and a phone number for all of these (if we store them as characters)?

- I’m storing 1,000,000 integers in a binary tree. Roughly how many nodes and levels can I expect the tree to have? Roughly how much space will it occupy on a 32-bit architecture?

## How Fast?
- My copy of Meyer’s Object Oriented Software Construction has about 1,200 body pages. Assuming no flow control or protocol overhead, about how long would it take to send it over an async 56k baud modem line?

- My binary search algorithm takes about 4.5mS to search a 10,000 entry array, and about 6mS to search 100,000 elements. How long would I expect it to take to search 10,000,000 elements (assuming I have sufficient memory to prevent paging).

- Unix passwords are stored using a one-way hash function: the original string is converted to the ‘encrypted’ password string, which cannot be converted back to the original string. One way to attack the password file is to generate all possible cleartext passwords, applying the password hash to each in turn and checking to see if the result matches the password you’re trying to crack. If the hashes match, then the string you used to generate the hash is the original password (or at least, it’s as good as the original password as far as logging in is concerned). In our particular system, passwords can be up to 16 characters long, and there are 96 possible characters at each position. If it takes 1mS to generate the password hash, is this a viable approach to attacking a password?

![alt text](https://ak.picdn.net/shutterstock/videos/2602358/thumb/3.jpg)

*fordítás: Milyen nagy? Milyen gyors?*

*Birtoklunk egy használható durva becslőképességet. Mielőtt kódolna, fel kell mérnie, hogy, mekkora lesz az adatstruktúra, vagy milyen gyorsan fog lefutni a kitérő. Minél gyorsabban meg tudja ezt csinálni, annál kissebb a kódolás problémája.
Tehát ez egy egyszerű kata: egy sor kérdés, mindegyik a durva/hozzávetőleges válaszra várva.Próbálj meg mindent a fejedben kidolgozni.Kb. egy hét múlva felteszem a válaszokat (ill. kidolgozásokat).*

*Milyen nagy?*

*Durván hány bináris adat szükséges az ábrázoláshoz:*

*1,000*
*1,000,000*
*1,000,000,000*
*1,000,000,000,000*
*8,000,000,000,000*

*A városomban hozzávetőlegesen 20,000 lakos van. Mennyi hely szükséges a neveik, címeik és a telefonszámaik tárolásához?(karakterenként tárolva az adatokat)*
*1,000,000 egész számot egy bináris fában tárolok. Nagyjából hány csomópontre és szintre számíthatok? Nagyjából mekkora helyet foglal mindez egy 32-bit-es szerkezetben?*

*Milyen gyors?*

*A Meyer's Object Oriented Software Construction tesztpéldányának 1,200 törzsoldalt tartalmaz. Feltételezve, hogy az adatáramlás nincs kontrollva vagy szabály által vezérelve, mennyi időbe telik a tovább küldése egy async 56k átviteli sebességű modem vonalon?*
*A bináris keresési algoritmusom 4.5mS alatt keres 10,000 belépési sort/tömböt, és 6mS alatt keres 100,000 elemet. Mennyi ideig tartana 10,000,000 elem esetében (feltéve, hogy elegendő memóriám van a lapozás megelőzésére).*
*Az Unix jelszavak tárolásához egy egyutas hash-függvényt használnak: az eredeti láncot átalakítják titkosított kódu lánccá, amely nem konvertálható vissza az eredetivé. A jelszó fájl megtámadásának egyik módja, hogy az összes lehetséges szöveges jelszót összeszedve, alkalmazzuk őketa jelszó-hash-re és ellenőrizzük, hogy az eredmény azonos-e a feltörendő jelszóval. Ha a hashek megegyeznek, akkor a generáláshoz használt karakterlánc az eredeti jelszó (vagy legalább annyira jó, mint az eredeti).*
*A speciális rendszerünkben, a jelszavak legfeljebb 16 karakter hosszúak lehetnek és 96 karakter használható. Ha 1 mS kell a jelszó-hash elkésztéséhez, akkor ez egy alkalmazható módszer?*
