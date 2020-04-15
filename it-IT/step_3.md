## Flatten the base of the body

Ora appiattisci la base del corpo per rendere il tuo insetto più realistico. Un modello con una base piatta è anche più facile da stampare in 3D!

Per fare ciò, puoi semplicemente rimuovere un cuboide dal tuo modello usando il blocco `differenza`{:class="blockscadsetops"}.

--- task ---

Per iniziare, crea un cuboide per coprire la metà inferiore dell'insetto (la parte che si trova sotto lo zero sull'asse Z).

Il cuboide dovrebbe essere `centrato` e alto 10 mm (lungo l'asse Z).

Aggiungi un blocco `trasla` per spostare il parallelepipedo -5mm lungo l'asse Z (in basso).

To make it easy to tell the cuboid and your bug's body apart, add a `color` block to make the cuboid a different colour.

![screenshot](images/bug-body-cuboid.png)

Il cuboide è più grande del corpo dell'insetto. Ciò significa che è possibile aggiungere elementi all'insetto senza dover ingrandire il cuboide in seguito.

--- /task ---

--- task ---

Use a `difference`{:class="blockscadsetops"} block to remove the cuboid from the body.

![screenshot](images/bug-difference.png)

Ora il corpo del tuo insetto ha una base piatta!

Trascina il tuo modello nel visualizzatore per vederlo da diverse angolazioni.

--- /task ---



  
