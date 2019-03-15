# EABdispersal
EAB sightings in Southern Ontario and proximity to population centres


Steps taken to visualize the data:

1) If the shapefiles are in a projected coordinate system, change the projection to WGS84
2) Convert all shapefiles (points,polygons) to KML in ArcMap
3) Use http://ogre.adc4gis.com/convert to convert the KML files into a geoJSON format
4) Import the geoJSON files into github
5) If using Leaflet, link the website through jQuery
