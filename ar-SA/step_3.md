## تسوية قاعدة الجسم

الآن قم بتسوية قاعدة الجسم لجعل الدعسوقة تبدو بشكل أكثر واقعي. النموذج ذو القاعدة المسطحة أسهل أيضًا في الطباعة ثلاثية الأبعاد!

للقيام بذلك، يمكنك ببساطة إزالة مكعب من النموذج الخاص بك بأستخدام كتلة ` difference `{: class = "blockscadsetops"}.

--- task ---

To start, create a cuboid to cover the bottom half of the bug (the part that sits below 0 on the Z axis).

The cuboid should be `centered` and 10mm tall (along the Z axis).

Add a `translate` block to move the cuboid -5mm along the Z axis (down).

To make it easy to tell the cuboid and your bug's body apart, add a `color` block to make the cuboid a different colour.

![screenshot](images/bug-body-cuboid.png)

The cuboid is bigger than the bug's body. This means you can add to the bug without needing to make the cuboid bigger later.

--- /task ---

--- task ---

Use a `difference`{:class="blockscadsetops"} block to remove the cuboid from the body.

![screenshot](images/bug-difference.png)

Now your bug's body has a flat base!

Drag your model around in the viewer to see it from different angles.

--- /task ---



  
