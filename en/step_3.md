## Flatten the base of the body

Now let's flatten the base of the body. This will make the bug more realistic. A model with a flat bottom is also easier to 3D print. 

+ To flatten the base of the bug, you can remove a cuboid from your model using the `difference` block. To see how this works, first let's create the cuboid. 

  The cuboid is centered and 10mm tall and translated -5mm along the Z axis (down) so that it covered the bottom half of the bug (the part that sits below 0 on the Z axis.)

  Using a different colour helps to see what's happening. 

  ![screenshot](images/bug-body-cuboid.png)

  The cuboid is bigger than it needs to be. This means you can add to be bug without needing to make the cuboid bigger later. 

+ Use a `difference`block to remove the cuboid from the body. 

  ![screenshot](images/bug-difference.png)

  Now your bug has a flat body. 

  Try dragging your model around in the viewer to see it from different angles. 





  
