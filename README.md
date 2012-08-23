![](https://raw.github.com/tmcw/mapmote/master/icon/icon128.png)

# mapmote

This is a tool for opening [JOSM](http://josm.openstreetmap.de/) from
arbitrary maps. It works with Leaflet, OpenLayers, and Modest Maps
maps consuming XYZ tiles (like MapBox, Stamen, etc), as well as Google
Maps (not MapsGL).

How it does this is a matter of extreme hackery; it detects and consumes
tile URLs, and then constructs a bounding box from their coordinates.
