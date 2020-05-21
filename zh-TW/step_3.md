## 拉平身體的底部

現在，拉平身體的底部，使你的昆蟲更加逼真。 具有平坦底座的模型也更易於3D列印！

為此，您可以使用 `difference`{:class="blockscadsetops"} 區塊從模型中刪除長方體。

--- task ---

首先，建立一個長方體以覆蓋昆蟲的下半部分（在Z軸上，位於0以下的部分）。

長方體應該是 `centered` 至10mm高（沿著Z軸）。

添加一個 `translate` 區塊以沿著Z軸（向下）移動長方體-5mm。

為了易於區分長方體和昆蟲的身體，請添加一個 `color` 區塊以使長方體成為不同的顏色。

![截圖](images/bug-body-cuboid.png)

此長方體大於昆蟲的身體。 這意味著您可以添加東西上去，而無需稍後再增大長方體。

--- /task ---

--- task ---

使用一個 `difference`{:class="blockscadsetops"} 區塊從身體上移除長方體。

![截圖](images/bug-difference.png)

現在，您的昆蟲的身體有一個平坦的底座了！

在查看器中四處拖動模型以從不同角度查看模型。

--- /task ---



  
