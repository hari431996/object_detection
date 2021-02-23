# object_detection
Malis course project

Damage estimation is a crucial part of any, disaster management team. In this project we try to detect level of damages in a image taken by a satellite using random forest model.

1. The objective is to predict the level of damage in images, starting from level-0(no damage) to level-3(Fully damaged).
2. First, we take the satellite images and make polygons around the objects in an image.
3. Then the building polygons will be flattened and fed to a random forest algorithm, whoch predicts whether if the object like for example buildings were damaged or not during the natural calamites. 
