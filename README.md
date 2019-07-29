Shapefile visualizer
===========================================================================================
Android application for visualizing shapefiles.

Author
-------
2019 Juan Manuel Fonseca-Solís, code modified from ESRI

Package Description
---
This package allows you to visualize shapefiles onto your mobile phone. For sample purposes, a shapefile with the districts of Costa Rica is provided [1]. 
The shapefile can be personalized with your own by changing the path on the "shapefile_path" string located on the strings.xml file. Before compiling and launching the app, you would need to copy the mentioned shapefile to the device using the following commands:
```
cd Distritos_de_Costa_Rica
adb push . /sdcard/ArcGIS/Samples/ShapeFile/Distritos_de_Costa_Rica/
```

**References:**
1. Portal de datos abiertos. Distritos de Costa Rica. URL: http://daticos-geotec.opendata.arcgis.com/datasets/741bdd9fa2ca4d8fbf1c7fe945f8c916_0
