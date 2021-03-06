## Створи тіло для свого жука

--- task ---

Відкрий редактор BlocksCAD у веббраузері [blockcad3d.com/editor/](https://www.blockscad3d.com/editor/){:target="_blank"}

--- /task ---

Тепер створи тіло свого жука.

--- task ---

Почни зі сфери (`sphere`) з радіусом `10` (одиниця вимірювання тут — міліметр):

![знімок екрана](images/bug-body-sphere.png)

Клацни на кнопку **Render** (Візуалізувати), щоб побачити результат.

Порада: ти можеш змінити колір візуалізованої моделі, натиснувши на кольоровий квадрат.

--- /task --- --- task ---

Тепер розтягни сферу вздовж осі Y, щоб створити витягнуте тіло для жука.

Блок `scale`{:class="blockscadtransforms"} дозволяє розтягувати або стискати об'єкти вздовж осей X, Y і Z. Встанови значення `1.2` для Y, щоб розтягнути сферу вздовж осі Y.

![знімок екрана](images/bug-body-y.png)

Знову клацни **Render** і перевір, що сфера була витягнута в еліпсоїд. Подивися на свою модель з різних сторін, щоб побачити, як вона змінилася.

--- /task ---

Порада: кожного разу, коли ти вносиш зміни до коду, тобі потрібно натиснути **Render**, щоб побачити результат.

--- task ---

Тепер стисни трохи еліпсоїд вздовж осі z, щоб зробити жука більш приплюснутим.

Встановлення значення менше `1` для осі робить об'єкт меншим уздовж цієї осі. Тож зміни значення Z у блоці `scale`{:class="blockscadtransforms"} на `0.8`.

![знімок екрана](images/bug-body-z.png)

--- /task ---




