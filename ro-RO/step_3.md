## Aplatizează baza corpului

Acum, aplatizează baza corpului pentru a-ți face insecta mai realistă. Un model cu o bază plată este de asemenea mai ușor de imprimat 3D!

Pentru a face acest lucru, poți pur și simplu să elimini un cuboid din model folosind blocul `difference`{:class="blockscadsetops"}.

--- task ---

Pentru a începe, creează un cuboid pentru a acoperi jumătatea inferioară a insectei (partea care stă sub 0 pe axa Z).

Cuboidul ar trebui să fie `centrat` și cu o înălțime de 10 mm (de-a lungul axei Z).

Adaugă un bloc `translate` pentru a muta cuboidul -5mm de-a lungul axei Z (jos).

Pentru ca să distingi mai ușor cuboidul de corpul insecttei tale, adaugă un bloc `color` pentru a face cuboidul să aibă o culoare diferită.

![captură de ecran](images/bug-body-cuboid.png)

Cuboidul este mai mare decât corpul insectei. Asta înseamnă că poți adăuga la insectă fără a fi nevoie să faci cuboidul mai mare mai târziu.

--- /task ---

--- task ---

Folosește un bloc `difference`{:class="blockscadsetops"} pentru a elimina cuboidul din corp.

![captură de ecran](images/bug-difference.png)

Corpul insectei are acum o bază plată!

Trage modelul din jurul vizualizatorului pentru a-l vedea din unghiuri diferite.

--- /task ---



  
