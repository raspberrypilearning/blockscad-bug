## Dejte své chybě tělo

--- task ---

Otevřete editor BlocksCAD ve webovém prohlížeči [blockscad3d.com/editor/](https://www.blockscad3d.com/editor/){: target = "_ blank"}

--- /task ---

Nyní vytvořte tělo své chyby.

--- task ---

Začněte `koulí` s poloměrem `10` (jednotka je zde milimetry):

![screenshot](images/bug-body-sphere.png)

Klepnutím na tlačítko **Vykreslit** zobrazíte výsledek.

Tip: Barvu vykresleného modelu můžete změnit kliknutím na barevný čtverec.

--- /task --- --- task ---

Nyní natáhněte kouli podél její osy Y a vytvořte tak protáhlé tělo pro chybu.

Blok `stupnice`{: class = "blockscadtransforms"} vám umožňuje natahovat nebo tlačit objekty podél os X, Y a Z. Nastavením hodnoty Y na `1,2` natáhnete kouli podél osy Y.

![screenshot](images/bug-body-y.png)

Klikněte znovu na **Vykreslit** a zkontrolujte, zda byla koule natažena do elipsoidu. Podívejte se na svůj model z různých úhlů, abyste viděli, jak se změnil.

--- /task ---

Tip: Pokaždé, když provedete změnu kódu, musíte kliknutím na **Vykreslit** zobrazit výsledky.

--- task ---

Nyní elipsoid rozmačkejte trochu podél osy z, abyste vytvořili plošší chybu.

Nastavením hodnoty osy pod `1` se objekt zmenší podél této osy. Změňte tedy hodnotu Z v bloku `stupnice`{: class = "blockscadtransforms"} na `0,8`.

![screenshot](images/bug-body-z.png)

--- /task ---




