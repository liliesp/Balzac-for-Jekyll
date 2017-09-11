---
layout: post-light-feature
title: Week One HW
description: "notes on readings and response"
categories: responses, impossiblemaps
date: 2017-09-10
---
I think for some intents and purposes, the styling differences between Apple and Google Maps do matter from a user perspective. I know I personally prefer to use Google Maps because I rely on public transportation at home, and Google Maps:

1. Labels public transportation
2. Can actually be a relatively good predictor of when public transportation will arrive/trip timing

(Although, this doesn't have a lot to do with its actual functionality as a map and goes more into using the map for a navigational purpose rather than to gain an understanding of an area.)

A couple of things I noticed/am wondering about the introduction to the cartography comparison piece:

* There is much more area-specific customization apparent in Apple Maps. Does this actually make it "better" or more meticulous? Is this a choice made to follow Apple's branding aesthetic? What does this add to the map?
* What is involved in map customization?

I'm thinking a lot about the part of the slideshow that compares bodies to maps and I think this is a helpful metaphor that I want to explore with my work in this class, but the more I think about it the less I think I actually agree with it. 

If maps are a projection (of 3D space, or even more if you include data being represented as another dimension) on 2D space (a screen in the case of web maps, conceptually any flat surface), then when you think of them in the more traditional sense they are less like bodies in that they can't react or change to stimuli-- the space can, but then you have to change the map. I guess I'm just grappling with the concept of a map as a body in the sense that we use our bodies, as individuals. Thinking about it in those terms is making me want to use that comparison to influence *how* I choose to represent data and space, and *why* I make my representational choices. It also invokes a sense of movement and emotion, and temporal recording. 

Following in that vein, the desire for and reach towards the universal map is kind of an interesting situation-- the universal map is probably the most impossible map of them all. I guess that doesn't mean that commercially, there might be a map that becomes the one standard, but the reason Apple and Google co-exsist is that they fill different needs and are accessible in slightly different ways.

#### comparing bodies and maps-- systems which interact and intertwine
if maps are, as a 2D representation of 3D space, are like bodies, can maps, web maps specifically, dance? act? interesting when thinking of web maps vs traditional maps and having larger systems of the body that are for something rather than 

instead of cells, maps have data
styles, tiles, servers

##### types of maps
* digital map: computer but not internet
* web map is a subtype type of digital map
* paper maps and atlases are very different
* also differentiates mobile maps
* google earth is a digital *globe*, not a map

##### history of web maps 
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
  * tiles are the *base layer*, layers like markers are placed over, which are called *data layers*, or content/feature layers
  * data layers are often vector-based, sometimes interactive

filetypes used: KML or GeoJSON

* alternative to raster tiles: vector tiles which render to rasters
* D3

#### Google Maps vs Apple Maps

1 billion google maps users?! so big

a platform, not just an app-- for example, uber uses google maps

concept of "the universal map" 

in comparison, Apple and Google maps look quite similar from afar

up close there are clearly diff icons (some icons on apple maps are personalized, which is a bit extra in my opinion but exactly what i expect from apple) 

color palette for google maps from far out seems more messy than apple's, but when you get close apple uses more bright colors

what do standard colors/local colors mean for the roads?

_WHAT IS LABELED?_

Google maps clearly labels transportation and then major attractions (ie stuff to do) whereas in the example given, apple labels mostly stuff to do, some shopping, and for some reason one food place. I think it's important that the hospital is on the Apple map but I am curious as to why. 

I see what their methodology was, but I would be interested to see a non-western city included.

re Showing default maps-- I'm curious how personalized maps work.

