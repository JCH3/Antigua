#Antigua Maps
##This excercise allows you to apply the skills learned in the Barbados exercise to Antigua.

1. Make a folder entitled "Antigua" on your computer.
2. Go to [DIVA GIS](http://www.diva-gis.org/gdata) and download the shapefiles for the administrative districts and roads of Antigua and Barbuda.
3. Open and extract the files within the new "Antigua" folder.
4. Open QGIS and begin a new project.
5. Set up "On the Fly" CRS.  Choose the **Geographic Coordinate Systems** "Antigua 1943" for your coordinates. 

![CRS OTF](/ScreenshotAntiguaCRS.png)

6. Build the basemap:
 * ATG_adm1; remove color fill or choose color that allows for some transparency and contrast with other colors.
 * ATG_roads; add as a vector layer.

![Base Map](/ScreenshotAntiguaBase.png) 

7. Import "Antigua 1775pts" and "Antigua 1824pts" from JCH3's _Antigua_ repository on Github into your Antigua folder.
8. Add "Antigua 1775pts" as raster layer. Adjust transparency so that you can see the base map and old map in contrast.

![Antigua Cartography](/ScreenshotAntiguaMap.png)

9. Unselect the "Antigua 1775pts" and add the "Antigua 1824pts" as a raster layer. Now you can switch back and forth between late eighteenth-century and early nineteenth-century cartographic conceptions of Antigua. Yay!
10. Save your work and close QGIS.