## <a href="https://leafletjs.com"><img src="https://github.com/emikhalev/leaflet-2gis/blob/master/logos/leaflet/img.png" height="24"></a> Leaflet 2GIS <a href="https://2gis.com/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/c1/2GIS_logo.svg" height="24"></a>
<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" height="18"/> &nbsp; <img src="https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=Leaflet&logoColor=white" height="18"/>

This plugin adds 2GIS support to the LeafletJS.

## Requirements
* Leaflet 0.7.3 or newer
* 2GIS api library (see example)

## Demo
See [demo](http://emikhalev.github.io/leaflet-2gis/)

# Examples
- [Leaflet 1.9.4 example](https://github.com/emikhalev/leaflet-2gis/blob/master/leaflet1.9.4_example.html)
- [Leaflet 0.7.3 example](https://github.com/emikhalev/leaflet-2gis/blob/master/leaflet0.7.3_example.html)

## Usage
```javascript
var map = new L.Map("map", {
    center: new L.LatLng(54.99014, 73.365319),
    zoom: 10,
    zoomAnimation: false,
    zoomDelta: 1,
    attributionControl: false
});

var dgis = new L.DGis();
map.addLayer(dgis);
```

## License
Leaflet 2GIS is free software, and may be redistributed under the <a href="https://github.com/emikhalev/leaflet-2gis/blob/master/LICENSE">MIT-LICENSE</a>.
