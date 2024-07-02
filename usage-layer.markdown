---
layout: page
title: 3.2 Layer Tool
permalink: /usage-layer/
---

# The Layer Tool

<img src="/assets/images/layer-tool.png" alt="Github release" style="border: 1px solid  gray">

The Layer tool works by use of an existing polygon layer as survey area. The project's CRS must be the same as the Layer's CRS that you are using for obtaining the data. **(When your source layer is in EPSG:3857, your QGIS Project should also be in EPSG:3857)**

After clicking the button on the Layer Tool, a dialog box will open, prompting you to select a polygon layer.

<img src="/assets/images/choose-layer.jpeg" alt="Github release" style="border: 1px solid  gray">

The polygon layer is used as following:

- in case no polygon is selected, all found polygons are used as survey areas
- in case one or more polygons are selected, each selected polygon is used as survey area

<img src="/assets/images/selected_polygons.jpeg" alt="Github release" style="border: 1px solid  gray">


