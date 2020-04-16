## Maak de basis van het lichaam plat

Maak nu de basis van het lichaam plat om je kever realistischer te maken. Een model met een platte basis is ook makkelijker om 3D te printen!

Om dit te doen, kun je eenvoudig een blok uit jouw model verwijderen met het blok `difference (verschil)`{:class="blockscadsetops"}.

--- task ---

Maak om te beginnen een balk om de onderste helft van de kever te bedekken (het deel dat onder de 0 op de Z-as zit).

De balk moet `centered` en 10 mm hoog zijn (langs de Z-as).

Voeg een `translate` blok toe om de balk -5 mm langs de Z-as (naar beneden) te verplaatsen.

Om het gemakkelijk te maken om de kubus en het lichaam van je insect uit elkaar te houden, voeg je een blok van `color` toe om de kubus een andere kleur te geven.

![schermafbeelding](images/bug-body-cuboid.png)

De balk is groter dan het lichaam van de kever. Dit betekent dat je het aan de kever kunt toevoegen zonder dat je de balk later groter hoeft te maken.

--- /task ---

--- task ---

Gebruik een `difference`{:class="blockscadsetops"} blok om de balk van het lichaam te verwijderen.

![schermafbeelding](images/bug-difference.png)

Nu heeft het lichaam van je insect een platte basis!

Sleep je model rond in het scherm om het vanuit verschillende hoeken te bekijken.

--- /task ---



  
