---
layout: single
comments: true
title: Visualizing Dar es salaam City Drone Imagery
published: true
---


![](https://raw.githubusercontent.com/samweli/jekyll-now/master/images/dar-drone-imagery-viz.png)

_Drone Imagery Map_

## Visualizing Dar es salaam drone imagery 2
At the end of 2017 The World Bank Tanzania helped in collecting drone imagery in Dar es salaam as per request of 
[DART](https://www.dart.go.tz/) (Dar Rapid Transit).

The activity covered all areas that are nearby all the planned BRT (Bus Rapid Transit) routes.

After successful imagery data collection, next it was required to visualize the collected data, 
one of the challenges in this was the raw data was too large to load in a normal computer, it took long time to view it,
 also the data format (geotiff) requires special GIS applications (most are desktop based) to access and view,
 this constrained users to first install those applications in order to view the data. 

These challenges raised a need to develop other tool (web based) in order to simplify data access and use.

As part of the World Bank Tanzania team which supported DART to collect the data I was tasked to create visualization for the drone imagery.

I decided to use [Mapbox GL](https://docs.mapbox.com/mapbox-gl-js/overview/) to build the web map which shows the imagery.

The result was a high perfomance and easily accessible web map. You can view it [here](http://brt-viz.herokuapp.com/)
