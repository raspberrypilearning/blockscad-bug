## Dóna forma a la teva cuca

--- task ---

Obre l'editor de BlocksCAD en un navegador web [blockscad3d.com/editor/](https://www.blockscad3d.com/editor/){:target="_ blank"}

--- /task ---

Ara crea el cos de la teva cuca.

--- task ---

Comença amb un bloc `sphere (esfera)` de radi `10` (la unitat aquí és en mil·límetres):

![captura de pantalla](images/bug-body-sphere.png)

Fes clic al botó **Render** per veure el resultat.

Consell: pots canviar el color del model generat fent clic al quadrat de colors.

--- /task --- --- task ---

Ara estira l'esfera al llarg del seu eix Y per crear un cos allargat per a la cuca.

El bloc `scale`{:class="blockscadtransforms"} permet estirar o comprimir objectes al llarg dels eixos X, Y i Z. Defineix el valor Y a `1,2` per estirar l’esfera al llarg de l’eix Y.

![captura de pantalla](images/bug-body-y.png)

Fes clic **Render** de nou i comprova que l'esfera s'ha estirat en un el·lipsoide. Mira el teu model des de diferents angles perquè puguis veure com ha canviat.

--- /task ---

Consell: cada vegada que es realitza un canvi en el codi, s'ha de fer clic a **Render** per veure els resultats.

--- task ---

Ara allisa l’el·lipsoide una mica al llarg de l’eix z per fer una cuca més planera.

Establir un valor d'eix inferior a `1` fa que l'objecte sigui més petit al llarg d'aquest eix. Per tant, canvia el valor Z en el bloc `scale`{:class="blockcadtransforms"} a `0,8`.

![captura de pantalla](images/bug-body-z.png)

--- /task ---




