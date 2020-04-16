## Dajte tijelu svoju bubu

--- task ---

Otvorite uređivač BlocksCAD u web-pregledniku [blockscad3d.com/editor/](https://www.blockscad3d.com/editor/){: target = "_ blank"}

--- /task ---

Sada stvorite tijelo svog buba.

--- task ---

Početi s `kugle` s radijusom od `10` (jedinica ovdje mm):

![screenshot](images/bug-body-sphere.png)

Kliknite na gumb **Render** da biste vidjeli rezultat.

Savjet: boju prikazanog modela možete promijeniti klikom na obojeni kvadrat.

--- /task --- --- task ---

Sada ispružite sferu duž svoje osi Y da biste stvorili izduženo tijelo za bubu.

Blok `ljestvice`{: class = "blockscadtransforms"} omogućuje vam rastezanje ili rezanje predmeta duž X, Y i Z osi. Postavite vrijednost Y na `1,2` kako biste razvukli sferu duž osi Y.

![screenshot](images/bug-body-y.png)

Kliknite ponovo **Render** i provjerite je li sfera istegnuta u elipsoid. Pogledajte svoj model iz različitih kutova kako biste vidjeli kako se promijenio.

--- /task ---

Savjet: svaki put kad napravite promjenu koda, trebate kliknuti **Render** da biste vidjeli rezultate.

--- task ---

Sada nasjeckajte elipsoid malo duž osi z, kako biste napravili ravnu kuku.

Postavljanjem vrijednosti osi ispod `1` objekt se smanjuje duž te osi. Stoga promijenite vrijednost Z u bloku `ljestvice`{: class = "blockcadtransforms"} u `0,8`.

![screenshot](images/bug-body-z.png)

--- /task ---




