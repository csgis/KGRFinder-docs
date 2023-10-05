---
layout: page
title: 3. Usage
permalink: /usage/
---

# Usage

The plugin adds a new toolbar with two Buttons

**D** = Draw Tool and **L** = Layer Tool

<img src="/assets/images/tools.jpeg" alt="Github release" style="border: 1px solid  gray">

In case the toolbar is hidden enable it in the "Toolbar" Menu:

<img src="/assets/images/toolbar.png" alt="Github release" style="border: 1px solid  gray">

### The Draw Tool

<img src="/assets/images/draw-tool.png" alt="Github release" style="border: 1px solid  gray">

When enabled, each left mouse click adds a corner point to the polygon on the map. Close the polygon with a right click.

<img src="/assets/images/polygon-draw.jpeg" alt="Github release" style="border: 1px solid  gray">

The red outline delineates the survey area that will serve as a bounding box for API requests.
After finishing the drawing, the returned features are added to the map.

<img src="/assets/images/closed-polygon.jpeg" alt="Github release" style="border: 1px solid  gray">

Whenever a search is performed, the KGR Finder Plugin adds a group of layers for polygons and point data.

<img src="/assets/images/layer-group.jpeg" alt="Github release" style="border: 1px solid  gray">


### The Layer Tool

<img src="/assets/images/layer-tool.png" alt="Github release" style="border: 1px solid  gray">

The Layer tool works by use of an existing polygon layer as survey area.

After clicking the button on the Layer Tool, a dialog box will open, prompting you to select a polygon layer.

<img src="/assets/images/choose-layer.jpeg" alt="Github release" style="border: 1px solid  gray">

The polygon layer is used as following:

- in case no polygon is selected, all found polygons are used as survey areas
- in case one or more polygons are selected, each selected polygon is used as survey area

<img src="/assets/images/selected_polygons.jpeg" alt="Github release" style="border: 1px solid  gray">

