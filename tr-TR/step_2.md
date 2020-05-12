## Böceğinize bir beden verin

--- task ---

BlocksCAD düzenleyicisini bir web tarayıcısında açın [blockscad3d.com/editor/](https://www.blockscad3d.com/editor/){: target = "_ blank"}

--- /task ---

Şimdi böceğinizin gövdesini oluşturun.

--- task ---

Yarıçapı `10` olan `küre` ile başlayın (buradaki birim milimetredir):

![ekran görüntüsü](images/bug-body-sphere.png)

Sonucu görmek için **Render** düğmesine tıklayın.

İpucu: renkli kareye tıklayarak oluşturulan modelin rengini değiştirebilirsiniz.

--- /task --- --- task ---

Böcek için uzun bir gövde oluşturmak için küreyi Y ekseni boyunca uzatın.

`scale`{: class = "blockscadtransforms"} bloğu, nesneleri X, Y ve Z eksenleri boyunca uzatmanıza veya ezmenize olanak tanır. Küreyi Y ekseni boyunca uzatmak için Y değerini `1.2` olarak ayarlayın.

![ekran görüntüsü](images/bug-body-y.png)

**Render** butonuna tekrar tıklayın ve kürenin elipsoit şekline dönüştüğünü kontrol edin. Modelinize farklı açılardan bakın, böylece nasıl değiştiğini görebilirsiniz.

--- /task ---

İpucu: kodda her değişiklik yaptığınızda, sonuçları görmek için **Render** 'a tıklamanız gerekir.

--- task ---

Şimdi daha düz bir hata yapmak için elipsoidi z ekseni boyunca biraz ezin.

Bir eksen değerinin `1` altına ayarlanması, nesneyi bu eksen boyunca küçültür. Bu yüzden `scale`{: class = "blockscadtransforms"} bloğundaki Z değerini `0.8` olarak değiştirin.

![ekran görüntüsü](images/bug-body-z.png)

--- /task ---




