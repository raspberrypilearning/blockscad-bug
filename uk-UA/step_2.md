## Подаруйте своєму клопі тіло

--- task ---

Відкрийте редактор BlocksCAD у веб-браузері [blockcad3d.com/editor/](https://www.blockscad3d.com/editor/){: target = "_ blank"}

--- /task ---

Тепер створіть тіло вашої помилки.

--- task ---

Почнемо з `сфери` з радіусом `10` (блок тут міліметрів):

![знімок екрану](images/bug-body-sphere.png)

Клацніть на кнопці **Render** щоб побачити результат.

Порада: ви можете змінити колір наданої моделі, натиснувши на кольоровий квадрат.

--- /task --- --- task ---

Тепер розтягніть сферу вздовж осі Y, щоб створити витягнуте тіло для клопа.

Блок `шкала`{: class = "блокуєтрансформації"} дозволяє розтягувати або розминати об'єкти вздовж осей X, Y і Z. Встановіть значення Y на `1,2` щоб розтягнути сферу вздовж осі Y.

![скріншот](images/bug-body-y.png)

Клацніть **Знову** ще раз і перевірте, чи сфера розтягнута на еліпсоїд. Подивіться на свою модель з різних кутів, щоб побачити, як вона змінилася.

--- /task ---

Порада: кожного разу, коли ви вносите зміни до коду, вам потрібно натиснути **Візуалізувати** щоб побачити результати.

--- task ---

Тепер розчавіть еліпсоїд трохи вздовж осі z, щоб зробити більш пологий помилку.

Встановлення значення осі нижче `1` робить об'єкт меншим уздовж цієї осі. Тож змініть значення Z у блоці `шкали`{: class = "блокирує переклади"} на `0,8`.

![скріншот](images/bug-body-z.png)

--- /task ---



