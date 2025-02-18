---
{"dg-publish":true,"permalink":"/world/grimtol/grimtol/"}
---

[[1 Index/Table of Contents\|Table of Contents]]
[[World/Grimtol/Salmyre/Salmyre\|Salmyre]]
[[World/Grimtol/Ockport\|Ockport]]
[[World/Grimtol/Carlens\|Carlens]]
[[World/Grimtol/Lorchester\|Lorchester]]
[[World/Grimtol/Hedron\|Hedron]]
[[World/Grimtol/Grimtol City\|Grimtol City]]
[[World/Grimtol/Calbridge\|Calbridge]]
[[World/Grimtol/Tolls Crossing\|Tolls Crossing]]
[[World/Grimtol/Lunar Lake\|Lunar Lake]]
[[World/Grimtol/Frozen Passes\|Frozen Passes]]
![Map New.png](/img/user/Z_Attachments/Map%20New.png)

```leaflet  
id: Grimtol ### Must be unique with no spaces  
image: [[Map New.png]] ### Link to the map image file  
bounds: [[0,0], [1536, 2048]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 800px ### Size of the leaflet embed in px on your screen  
width: 60% ### Size of the leaflet embed in your note  
lat: 768 ### To center the map, make this half of the map height.  
long: 1024 ### To center the map, make this half of the map width.  
minZoom: -1 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: .05 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: .15 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```
