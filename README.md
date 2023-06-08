## <a href="https://leafletjs.com"><img src="https://github.com/emikhalev/leaflet-2gis/blob/master/logos/leaflet/img.png" width="64"></a> Leaflet 2GIS <a href="https://2gis.com/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/c1/2GIS_logo.svg" width="48"></a>

<span style="font-size: 18px">This plugin add 2GIS support to the leaflet.</span>

## Requirements
* Leaflet 0.6 or newer
* 2GIS api library (see example)

## Demo
See [demo](http://emikhalev.github.io/leaflet-2gis/)

## Usage
```javascript
var map = new L.Map("map", {
	center: new L.LatLng(54.99014, 73.365319), 
	zoom: 10,
	zoomAnimation: true 
});
var dgis = new L.DGis();
map.addLayer(dgis);
```

## License
Leaflet 2GIS is free software, and may be redistributed under the MIT-LICENSE.
