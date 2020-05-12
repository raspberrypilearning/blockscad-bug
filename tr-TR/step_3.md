## Vücudun tabanını düzleştirin

Şimdi böceğinizi daha gerçekçi hale getirmek için vücudun tabanını düzleştirin. Düz tabanlı bir modelin 3D baskısı da daha kolaydır!

Bunu yapmak için, `difference`{: class = "blockscadsetops"} bloğunu kullanarak bir küboidi modelinizden kaldırabilirsiniz.

--- task ---

Başlamak için, böceğin alt yarısını (Z ekseninde 0'ın altında oturan kısım) kapsayacak şekilde bir küboid oluşturun.

Küboid `centered` ve 10 mm yüksekliğinde olmalıdır (Z ekseni boyunca).

Küboid -5mm Z ekseni boyunca (aşağı) hareket etmek için `translate` blok ekleyin.

Küboid ve böceğinizin vücudunu ayırt etmeyi kolaylaştırmak için, küboidi farklı bir renk yapmak üzere `color` bloğunu ekleyin.

![ekran görüntüsü](images/bug-body-cuboid.png)

Küboid, böceğin vücudundan daha büyüktür. Bu, küboidi daha sonra büyütmeye gerek kalmadan böceğe ekleyebileceğiniz anlamına gelir.

--- /task ---

--- task ---

Küboidi vücuttan kaldırmak için `difference`{: class = "blockscadsetops"} bloğunu kullanın.

![ekran görüntüsü](images/bug-difference.png)

Şimdi böceğinizin vücudunun düz bir tabanı var!

Modelinizi farklı açılardan görmek için görüntüleyicide sürükleyin.

--- /task ---



  
