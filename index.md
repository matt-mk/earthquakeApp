---
title       : Interactive Earthquake Map
subtitle    : examine the earthquakes dataset included in R
author      : M Clifton
job         : Data Scientist
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
github:
          user: matt-mk
          repo: earthquakeApp

knit        : slidify::knit2slides

--- .class #id 

## Earthquake App

1. This app uses the quake dataset found within R
2. It utilises the Leaflet package providing a background against which earthquake data can be mapped.
3. The data includes:
  + the latitude and longitude of earthquakes around Fiji
  + the magnitude of the earthquakes
  + information pertaining to earthquakes with a magnitude greater than 4

--- 

## Screen Shot

![](Capture.png) 

--- 

## Using the App

1. Check/Uncheck the checkbox if you would like the legend to be visible
2. Slide the slidebar to determine which quakes should be displayed by magnitude
3. Set your reactive colour options with the palette control

---

## Why is this app interesting?

This app is interesting because it provides a template against which geographic data and information may be displayed in a compelling and interactive manner.

Location and place are not the same, and places have physical and human attributes.  
Geointelligence is about the integration of both and maps such as these provide the opportunity to investigate how places interact with one another.

Using R to map geographical information therefore helps to develop cognitive thinking about places.

