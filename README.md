![](https://raw.github.com/tmcw/mapmote/master/icon/icon128.png)

## Install

[Download mapmote.crx from this repository](https://github.com/downloads/tmcw/mapmote/mapmote.crx)

1. Download and save mapmote.crx
2. Click the wrench icon on the browser toolbar.
3. Select Tools > Extensions.
4. Locate the extension file on your computer and drag the file onto the Extensions page.
5. Click Install.

**OR** [see this bookmarklet version](http://bl.ocks.org/d/3436481/) and drag & drop to your
bookmarks bar.

## Using

![](https://raw.github.com/tmcw/mapmote/master/screenshot.png)

1. Open [JOSM](http://josm.openstreetmap.de/)
2. Have a tiled map open to a specific area of the world in your browser
3. Click on mapmote, and JOSM should begin downloading the area for editing.

# mapmote

This is a tool for opening [JOSM](http://josm.openstreetmap.de/) from
arbitrary maps. It works with Leaflet, OpenLayers, and Modest Maps
maps consuming XYZ tiles (like MapBox, Stamen, etc), as well as Google
Maps (not MapsGL).

How it does this is a matter of extreme hackery; it detects and consumes
tile URLs, and then constructs a bounding box from their coordinates.

# License is BSD
