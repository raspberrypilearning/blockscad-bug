## Geef je kever een lichaam

--- task ---

Open de BlocksCAD-editor in een webbrowser [blockscad3d.com/editor/](https://www.blockscad3d.com/editor/){:target="_blank"}

--- /task ---

Maak nu het lichaam van je kever.

--- task ---

Begin met een `sphere (bol)` met een straal van `10` (de eenheid is hier millimeters):

![schermafbeelding](images/bug-body-sphere.png)

Klik op de knop **Render** om het resultaat te zien.

Tip: je kunt de kleur van het gerendeerde model wijzigen door op het gekleurde vierkant te klikken.

--- /task --- --- task ---

Rek nu de bol uit langs zijn Y-as om een langwerpig lichaam voor de kever te creëren.

Met het blok `scale (schaal)`{:class="blockscadtransforms"} kun je objecten uitrekken of platdrukken langs de X-, Y- en Z-assen. Stel de Y-waarde in op `1.2` om de bol langs de Y-as uit te rekken.

![schermafbeelding](images/bug-body-y.png)

Klik opnieuw op **Render** en controleer of de bol is uitgerekt tot een ellips. Bekijk je model vanuit verschillende hoeken, zodat je kunt zien hoe het is veranderd.

--- /task ---

Tip: elke keer dat je de code wijzigt, moet je op **Render** klikken om de resultaten te zien.

--- task ---

Plet nu de ellips een beetje langs de z-as om een plattere kever te maken.

Als je een as-waarde onder `1` instelt, wordt het object langs die as kleiner. Verander dus de Z-waarde in het `scale`{:class="blockscadtransforms"} blok in `0.8`.

![schermafbeelding](images/bug-body-z.png)

--- /task ---




