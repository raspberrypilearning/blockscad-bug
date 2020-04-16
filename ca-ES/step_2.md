## Dóna forma a la teva cuca

--- task ---

Obre l'editor de BlocksCAD en un navegador web [blockscad3d.com/editor/](https://www.blockscad3d.com/editor/){:target="_ blank"}

--- /task ---

Ara crea el cos de la teva cuca.

--- task ---

Start with a `sphere` with a radius of `10` (the unit here is millimetres):

![screenshot](images/bug-body-sphere.png)

Click on the **Render** button to see the result.

Tip: you can change the colour of the rendered model by clicking on the coloured square.

--- /task --- --- task ---

Now stretch the sphere along its Y axis to create an elongated body for the bug.

The `scale`{:class="blockscadtransforms"} block allows you to stretch or squash objects along the X, Y, and Z axes. Set the Y value to `1.2` to stretch the sphere along the Y axis.

![screenshot](images/bug-body-y.png)

Click **Render** again and check that the sphere has been stretched into an ellipsoid. Look at your model from different angles so you can see how it has changed.

--- /task ---

Tip: every time you make a change to the code, you need to click **Render** to see the results.

--- task ---

Now squash the ellipsoid a bit along the z-axis to make a flatter bug.

Setting an axis value below `1` makes the object smaller along that axis. So change the Z value in the `scale`{:class="blockscadtransforms"} block to `0.8`.

![screenshot](images/bug-body-z.png)

--- /task ---




