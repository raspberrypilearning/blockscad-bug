## Dă-ți un corp de eroare

--- task ---

Deschide editorul BlocksCAD într-un browser web [blockscad3d.com/editor/](https://www.blockscad3d.com/editor/){: target = "_ blank"}

--- /task ---

Acum creează corpul erorii tale.

--- task ---

Începeți cu `sferă` cu o rază de `10` (unitatea de aici este milimetrică):

![captură de ecran](images/bug-body-sphere.png)

Faceți clic pe butonul **Render** pentru a vedea rezultatul.

Sfat: puteți modifica culoarea modelului redat făcând clic pe pătratul colorat.

--- /task --- --- task ---

Acum întinde sfera de-a lungul axei sale Y pentru a crea un corp alungit pentru bug.

Blocul `scara`{: class = "blockcadtransforms"} vă permite să întindeți sau să stricați obiecte de-a lungul axelor X, Y și Z. Setați valoarea Y la `1,2` pentru a întinde sfera de-a lungul axei Y.

![captură de ecran](images/bug-body-y.png)

Faceți clic pe **Render** din nou și verificați dacă sfera a fost întinsă într - un elipsoid. Privește-ți modelul din diferite unghiuri pentru a putea vedea cum s-a schimbat.

--- /task ---

Sfat: de fiecare dată când efectuați o modificare a codului, trebuie să faceți clic pe **Render** pentru a vedea rezultatele.

--- task ---

Acum zdrobiți elipsoidul un pic de-a lungul axei z pentru a face un bug mai plat.

Setarea unei valori a axei sub `1` face ca obiectul să fie mai mic de-a lungul acelei axe. Așadar, modificați valoarea Z în scara ``{: class = "blockcadtransforms"} bloc la `0,8`.

![captură de ecran](images/bug-body-z.png)

--- /task ---




