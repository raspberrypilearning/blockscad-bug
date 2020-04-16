## Aplana la base del cos

Ara aplana la base del cos per fer la teva cuca més realista. Un model amb base plana també és més fàcil d'imprimir en 3D!

Per fer-ho, simplement pots eliminar un cuboide del teu model mitjançant el block `difference`{:class="blockscadsetops"}.

--- task ---

Per començar, crea un cuboide per cobrir la meitat inferior de la cuca (la part que se situa per sota de 0 a l’eix Z).

El cuboide hauria d’estar `centrat` i tenir 10 mm d’alçada (al llarg de l’eix Z).

Afegeix un bloc `translate` per moure el cuboide -5mm per l’eix Z (cap avall).

Perquè sigui més fàcil distingir el cuboide i el cos de la cuca, afegeix un bloc `color` per fer que el cuboide tingui un color diferent.

![captura de pantalla](images/bug-body-cuboid.png)

El cuboide és més gran que el cos de la cuca. Això vol dir que pots afegir-lo a la cuca sense haver de fer-lo més gran més endavant.

--- /task ---

--- task ---

Utilitza un bloc `difference`{:class="blockscadsetops"} per eliminar el cuboide del cos.

![captura de pantalla](images/bug-difference.png)

Ara el cos de la teva cuca té una base plana!

Arrossega el model pel visor per veure-ho des de diferents angles.

--- /task ---



  
