## Srovnejte spodní část těla

Nyní vyrovnejte základnu těla, aby vaše chyba byla realističtější. Model s rovnou základnou je také snadnější pro 3D tisk!

Chcete-li to provést, můžete jednoduše odstranit kvádr z vašeho modelu pomocí bloku `rozdílu`{: class = "blockscadsetops"}.

--- task ---

Nejprve vytvořte kvádr, který pokryje spodní polovinu chyby (část, která leží pod 0 na ose Z).

Kvádr by měl být `vystředěn na` a 10 mm vysoký (podél osy Z).

Chcete-li pohybovat kvádrem -5 mm podél osy Z (dolů), přidejte blok `překlad`.

Chcete-li usnadnit rozeznání kvádru a těla chyby od sebe, přidejte blok `barvy` aby se kvádr stal jinou barvou.

![screenshot](images/bug-body-cuboid.png)

Kvádr je větší než tělo chyby. To znamená, že můžete přidat k chybě, aniž byste museli později kvádr zvětšit.

--- /task ---

--- task ---

Pomocí bloku `rozdíl`{: class = "blockscadsetops"} odeberete kvádr z těla.

![screenshot](images/bug-difference.png)

Nyní má tělo vaší chyby plochý základ!

Přetažením modelu v prohlížeči jej můžete vidět z různých úhlů.

--- /task ---



  
