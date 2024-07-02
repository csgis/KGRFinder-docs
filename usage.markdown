---
layout: page
title: 3. Usage
permalink: /usage/
---

# Usage

## General


### Toolbar
The plugin adds a new toolbar with two Buttons

**D** = Draw Tool and **L** = Layer Tool

<img src="/assets/images/tools.jpeg" alt="tools" style="border: 1px solid  gray">

In case the toolbar is hidden enable it in the _Toolbar_ Menu:

<img src="/assets/images/toolbar.png" alt="toolbar" style="border: 1px solid  gray">

### Survey size warning

In case the survey area is larger than 1000.00 km2, a warning is shown as this might result in a very large API request.

<img src="/assets/images/warning.jpeg" alt="warning" style="border: 1px solid  gray">

### Information about found data

Take note of the status messages at the top of the map window. A green success message informs about a successful search.
A orange warning means no data has been returned from a API.

<img src="/assets/images/status.jpeg" alt="status" style="border: 1px solid  gray">

### Attribute table

The created layer is filled with the returned data. This is generalized for both APIs.
The source column shows the API source. Tags are special for OSM and will only be filled in OSM API requests.
In case no data is retuned for a column a "-" is used.

<img src="/assets/images/data.jpeg" alt="data" style="border: 1px solid  gray">

## The Draw Tool

<img src="/assets/images/draw-tool.png" alt="drawing" style="border: 1px solid  gray">

**We suggest to work in EPSG:3857!**

When enabled, each left mouse click adds a corner point to the polygon on the map. Close the polygon with a right click.

<img src="/assets/images/polygon-draw.jpeg" alt="drawing" style="border: 1px solid  gray">

The red outline draws the survey area that will serve as a bounding box for API requests.
After finishing the drawing, the found features are added to the map.

<img src="/assets/images/closed-polygon.jpeg" alt="polygon" style="border: 1px solid  gray">

Whenever a search is performed, the KGR Finder Plugin adds a group of layers for polygons and point data. With a point and polygon Layer and two styles for iDAI.gazeteer or OSM data.

<img src="/assets/images/layer-group.jpeg" alt="layer group" style="border: 1px solid  gray">





## The Layer Tool

<img src="/assets/images/layer-tool.png" alt="Github release" style="border: 1px solid  gray">

The Layer tool works by use of an existing polygon layer as survey area. The project's CRS must be the same as the Layer's CRS that you are using for obtaining the data. **(When your source layer is in EPSG:3857, your QGIS Project should also be in EPSG:3857)**

After clicking the button on the Layer Tool, a dialog box will open, prompting you to select a polygon layer.

<img src="/assets/images/choose-layer.jpeg" alt="Github release" style="border: 1px solid  gray">

The polygon layer is used as following:

- in case no polygon is selected, all found polygons are used as survey areas
- in case one or more polygons are selected, each selected polygon is used as survey area

<img src="/assets/images/selected_polygons.jpeg" alt="Github release" style="border: 1px solid  gray">


