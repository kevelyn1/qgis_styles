# Papercut style
This style enables to create papercut style. To use the style, please copy together with paper_texture.png file to your folder and replace in .qml file the folderpath of the paper_texture.png file.
Currently includes:
 - elevation style (papercut_relief.qml). To use this style, your elevation data needs to be in vector format and all evelavtion intervals as polygons on top of each other. The attribute table needs to have an attribute "Elevation" where values (integers) are 10, 20, 30, 40, 50, 60, 70, 80, 90, 100, 120, 140, 160, 180, 200, 250, 280. You don't need to have all the values but it's how I had my elevation data. You can also just reclassify your data.
