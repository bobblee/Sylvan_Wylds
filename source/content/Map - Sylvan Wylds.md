---
mapCalc1: 0.09328358208955223
title: Area Map
map_height_y: 4096
map_width_x: 3072
scale_pixels: 268
scale_pixels_range: 25
draft: true
---

```leaflet  
id: SylvanWylds01 ### Must be unique with no spaces  
image: [[SylvanWylds.png]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [4096, 3072]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 100% ### Size of the leaflet embed in px on your screen  
width: 95% ### Size of the leaflet embed in your note  
lat: 2048 ### To center the map, make this half of the map height.  
long: 1536 ### To center the map, make this half of the map width.  
minZoom: -2.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 0 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1.5 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: day ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.05228358208955223 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```
