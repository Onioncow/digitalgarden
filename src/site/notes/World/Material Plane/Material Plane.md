---
{"dg-publish":true,"permalink":"/world/material-plane/material-plane/"}
---


```leaflet  
id: MapCalcExample ### Must be unique with no spaces  
image: [[City_Map_LowRes.jpg]]### Link to the map image file. Do not add a ! in front of the image 
image: [[Nation_Map_LowRes.jpg]]### Link to the map image file. Do not add a ! in front of the image  
image: [[Continents_Map.jpg]]### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [4960, 7016]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 1050px ### Size of the leaflet embed in px on your screen  
width: 95% ### Size of the leaflet embed in your note  
lat: 2480 ### To center the map, make this half of the map height.  
long: 3508 ### To center the map, make this half of the map width.  
minZoom: -3 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.09328358208955223 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```
