---
layout: post
comments: true
title: Converting ODK location data to WKT in QGIS
published: true
---


![](https://raw.githubusercontent.com/samweli/jekyll-now/master/images/odktrace2wkt.png)

_Plugin interface_

## Loading ODK location data in QGIS

ODK is now widely used in collecting location data, one of its use case is the project called Ramani Huria (Open Map) which use ODK to map Dar es salaam city drains. One of the challenges in using ODK to collect linestring data is the format that it save the data into (geotrace), the format currently is not a standard that is supported in GIS applications.

This cause issues in importing the data into GIS applications for use after collection. Ramani Huria team was faced with this problem and they wrote script that convert the data from geotrace to Well-Known text format which is widely used standard. 

The issue with scripts is they are not very user friendly, so they gave me a task to work on building a QGIS plugin which will be easy for a normal user to use.

I developed the plugin by building upon the work that Ramani Huria had already started. Since the team had a [script](https://github.com/ivangayton/ODK_geotrace_to_WKT/blob/master/lines_to_wkt.py) written in python.

The plugin works on  all QGIS 3 versions.
To use it, open QGIS Desktop, then click Plugins menu -> Manage and Install plugins, search for ODKTrace2WKT, click Install.

After installing is finished, an icon of blue arrow will be added to the QGIS plugins panel, click it to load the plugin.
[How to use video](https://www.youtube.com/watch?v=GvxkoVP0-Dc)


[Plugin repository](https://plugins.qgis.org/plugins/odktrace2wkt/)

[Source code](https://github.com/Samweli/odktrace2wkt)


