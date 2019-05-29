# EABdispersal
Chloropleth map of EAB sightings in various counties of Southern Ontario and their proximity to population centres


Steps taken to visualize the EAB data:

1) Change projection of the shapefiles to WGS84
2) Convert all shapefiles (points,polygons) to KML
3) Use http://ogre.adc4gis.com/convert to convert the KML files into a geoJSON format
4) Import the geoJSON files into github
5) If using Leaflet, link the website through jQuery
