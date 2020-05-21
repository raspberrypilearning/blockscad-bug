## 給你的昆蟲一個身體

--- task ---

在Web瀏覽器中打開BlocksCAD編輯器 [blockscad3d.com/editor/](https://www.blockscad3d.com/editor/){:target="_blank"}

--- /task ---

現在，建立你的昆蟲的身體。

--- task ---

從半徑為 `10` 的 `sphere` 球體開始（這裡的單位是毫米）：

![截圖](images/bug-body-sphere.png)

點擊 **Render** 按鈕來查看結果。

提示：您可以通過點擊彩色正方形來更改渲染模型的顏色。

--- /task --- --- task ---

現在，沿著球體的Y軸延伸球體，來為昆蟲建立細長的身體。

`scale`{:class="blockscadtransforms"} 區塊使你可以沿著X，Y和Z軸延展或壓縮物件。 將Y值設定為 `1.2` 來沿著Y軸延展球體。

![截圖](images/bug-body-y.png)

再次點擊 **Render** ，然後檢查球體是否已延展為橢圓體。 從不同角度查看模型，以便了解其變化。

--- /task ---

提示：每次你更改程式碼時，都需要點擊 **Render** 以查看結果。

--- task ---

現在，沿z軸稍微壓縮橢圓形，以製作出更扁平的昆蟲。

將軸值設置為低於 `1` 可使對象沿著該軸變小。 因此，將  `scale`{:class="blockscadtransforms"} 區塊中的Z值更改為 `0.8`。

![截圖](images/bug-body-z.png)

--- /task ---




