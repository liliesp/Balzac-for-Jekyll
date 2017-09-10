---
layout: post-light-feature
title: Week One HW
description: "notes on readings and response"
categories: responses, impossiblemaps
date: 2017-09-10
---

####comparing bodies and maps-- systems which interact and intertwine
can maps, web maps specifically, dance? act?
instead of cells, maps have data
styles, tiles, servers

#####types of maps
* digital map: computer but not internet
* web map is a subtype type of digital map
* paper maps and atlases are very different
* also differentiates mobile maps
* google earth is a digital _globe_, not a map

#####history of web maps 
* ArcGIS
* 1996 -- MapQuest
  * MapQuest sucked for several reasons: full page refresh to scroll or zoom, aligned to tile boundaries
* 2005 -- Google Maps
  * The difference is in the tiles. Tiles can be any raster image
  * little tiles load faster than one big piece
  * "smart" maps load tiles outside the screen too-- facilitates scrolling; called a **slippy map**
  * each zoom level has its own set of tiles, starts at one for the whole world and increases exponentially
  * tiles rendered in advance and stored in cache; can be accessed individually
  * server/zoomlevel/xpos/ypos
  * **Mercator projection** is used because it works well for flat maps
  * tiles are the _base layer_, layers like markers are placed over, which are called _data layers_, or content/feature layers
  * data layers are often vector-based, sometimes interactive

filetypes used: KML or GeoJSON

* alternative to raster tiles: vector tiles which render to rasters
* D3

####Google Maps vs Apple Maps

1 billion google maps users?! so big

a platform, not just an app-- for example, uber usees google maps

"the universal map" 

in comparison, Apple and Google maps look quite similar from afar

up close there are clearly diff icons (some icons on apple maps are personalized, which is a bit extra in my opinion but exactly what i expect from apple) 

color palette for google maps from far out seems more messy than apple's, but when you get close apple uses more bright colors

what do standard colors/local colors mean for the roads?

_WHAT IS LABELED?_

Google maps clearly labels transportation and then major attractions (ie stuff to do) whereas in the example given, apple labels mostly stuff to do, some shopping, and for some reason one food place. I think it's important that the hospital is on the Apple map but I am curious as to why. 

I know personally Google maps is considered to be really reliable and helpful for planning trips on public transport and predicting arrivals (at least in some places with some service) but I was actually really surprised Apple actively doesn't label public transport. 

I see what their methodology was, but I would be interested to see a non-western city included.

re Showing default maps-- I'm curious how personalized maps work.



