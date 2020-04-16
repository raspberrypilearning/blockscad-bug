## Dajte svojmu telu chybu

--- task ---

Otvorte editor BlocksCAD vo webovom prehliadači [blockscad3d.com/editor/](https://www.blockscad3d.com/editor/){: target = "_ blank"}

--- /task ---

Teraz vytvorte telo svojej chyby.

--- task ---

Začnite `guľou` s polomerom `10` (jednotka je tu milimetre):

![snímka obrazovky](images/bug-body-sphere.png)

Kliknutím na tlačidlo **Render** zobrazíte výsledok.

Tip: farbu vykresleného modelu môžete zmeniť kliknutím na farebný štvorec.

--- /task --- --- task ---

Teraz natiahnite guľu pozdĺž jej osi Y a vytvorte pre ňu pretiahnuté telo.

`stupnice`{: class = "blockscadtransforms"} blok umožňuje natiahnuť alebo squash predmety pozdĺž X, Y a Z osi. Nastavte hodnotu Y na `1,2` aby ste natiahli guľu pozdĺž osi Y.

![snímka obrazovky](images/bug-body-y.png)

Znovu kliknite na **Render** a skontrolujte, či bola guľa roztiahnutá do elipsoidu. Pozrite sa na svoj model z rôznych uhlov, aby ste videli, ako sa zmenil.

--- /task ---

Tip: Vždy, keď urobíte zmenu kódu, musíte kliknúť na **Vykresliť** aby ste videli výsledky.

--- task ---

Teraz vypláchnite elipsoid trochu pozdĺž osi Z, aby sa vytvorila ploššia chyba.

Nastavením hodnoty osi pod `1` sa objekt zmenší pozdĺž tejto osi. Preto zmeňte hodnotu Z v bloku `stupnica`{: class = "blockscadtransforms"} na `0,8`.

![snímka obrazovky](images/bug-body-z.png)

--- /task ---




