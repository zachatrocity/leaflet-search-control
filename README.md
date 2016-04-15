# leaflet-search-control
A simple boilerplate for building your own leaflet search control

#How to use
- add `leaflet-search-control.js` to your project after leaflet.js has been loaded.
- add to your map:
```
	var map = L.map('map').setView([34.5259,-92.1588], 7);

	L.tileLayer('http://{s}.tile.osm.org/{z}/{x}/{y}.png', {
	    attribution: '&copy; <a href="http://osm.org/copyright">OpenStreetMap</a> contributors'
	}).addTo(map);

	//add search control to map
	L.control.search({}).addTo(map);
```
- customize it to fit your needs in `leaflet-search-control.js` specifically the `keyp` and `itemSelected` selected functions