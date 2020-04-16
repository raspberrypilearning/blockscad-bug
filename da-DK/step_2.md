## Giv din bug en krop

--- task ---

Åbn BlocksCAD-editoren i en webbrowser [blockscad3d.com/editor/](https://www.blockscad3d.com/editor/){: target = "_ blank"}

--- /task ---

Opret nu kroppen på din bug.

--- task ---

Start med en `sfære` med en radius på `10` (enheden her er millimeter):

![skærmbillede](images/bug-body-sphere.png)

Klik på **Render** knappen for at se resultatet.

Tip: du kan ændre farven på den gengivne model ved at klikke på det farvede firkant.

--- /task --- --- task ---

Stræk nu kuglen langs dens Y-akse for at skabe en langstrakt krop til bugten.

`skalaen`{: class = "blockscadtransforms"} -blokken giver dig mulighed for at strække eller squash objekter langs X-, Y- og Z-akserne. Indstil Y-værdien til `1,2` at strække kuglen langs Y-aksen.

![skærmbillede](images/bug-body-y.png)

Klik på **Render** igen, og kontroller, at kuglen er strækket ind i en ellipsoid. Se på din model fra forskellige vinkler, så du kan se, hvordan den har ændret sig.

--- /task ---

Tip: hver gang du foretager en ændring af koden, skal du klikke på **Render** at se resultaterne.

--- task ---

Drej nu ellipsoiden lidt langs z-aksen for at lave en fladere bug.

Indstilling af en akseværdi under `1` gør objektet mindre langs den akse. Så ændre Z-værdien i `skala`{: class = "blockscadtransforms"} -blok til `0,8`.

![skærmbillede](images/bug-body-z.png)

--- /task ---




