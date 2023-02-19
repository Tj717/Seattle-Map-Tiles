# Seattle Medical Centers Map Tiles

> [Link](https://tj717.github.io/Seattle-Medical-Centers-Map-Tiles) to access the map.

This map aims to visualize the locations of the medical centers in the Seattle area.  The map is created using the Mapbox API, styled using Mapbox Studio, and hosted on GitHub Pages. The tile sets are generated from QGIS's QMetaTiles and use WMS to connect with Mapbox Studio's base maps.

## First Layer: Base map 
![Layer 1](/img/map1.png)
- Zoom level: 10 - 14
- This layer is a custom map designed on top of Mapbox Studio's sky-blue street map.  The map is designed to be bright, clean, and easy to read. Blue also is a good contrast to red, which is the primary color of the hospital icons.

## Second Layer: Hospitals
![Layer 2](/img/map2.png)
- Zoom level: 10 - 14
- This layer is a simple dot map of the location of Seattle's medical center. The dataset comes from [Seattle Open Data](https://data.seattle.gov/dataset/Hospitals/5972-b4xx).

## Third Layer: Hospitals + Base Map
![Layer 3](/img/map3.png)
- Zoom level: 10 - 14
- This layer is the combination of the base layer and the hospital layer.

## Fourth Layer: Bright-Themed Map
![Layer 4](/img/map4.png)
- Zoom level: 10 - 14
- This layer is a custom map style I designed using Mapbox Studio. I adjusted the size of the icons and the color of the water and the land to make the map's color more soothing and bright. The warm colors of the base map also serve as a good contrast to the colors of the icons of the hospitals if the users want to combine the two layers.





