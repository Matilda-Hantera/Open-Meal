---
layout: default
title: "Open Meal Information"
---
# Welcome to Open Information for Meals!

The goal is to create a way to create open data about menus, ingredients, nutritional values and allergens in a consistent way. We want to make it as easy as possible to reuse the information. We are hoping that the specification will be used by many not only in Sweden as to make using the information fun and easy.

The specification and other information for how to create open meal information can be found on this webpage and as it is on Github anyone can fork and develop it. There are two implementations of the specification:

* An [API](/Open-Meal/doc/basics.html) with the full data set in JSON format
* [iCalendar](/Open-Meal/doc/icalendar.html) with a subset of the information. The calendar-feed can be used by smartphones and pads as well as other calendar software to subscribe to the information.

Questions and suggestions can be submitted as issus in the repository. For Swedish users [comments and discussion can be chaneled through the national dataportals community](https://community.dataportal.se/topic/171/måltidsinformation-som-öppna-data-hur-du-publicerar?_=1652685653024).

## Version of the specification

| Version | Description |
| :--- | ---: |
| 2.0 | [The first version of the specification](https://orebrokommun.github.io/Open-Meal-Information/) was created by the municipality of Örebro in 2015. |
| 3.1 | The project NSÖD created [an updated version of the specification](https://www.dataportal.se/sv/specifications/Mltidsinformation/NSOD#ref=?p=1&q=m%C3%A5ltid&s=2&t=20&f=&rt=spec_standard%24spec_profile&c=false) in 2021. |
| 3.2 | The current version of the specification as seen in this repository |

## Example

This is an example of [an iCalendar feed available for subscription for the school ”Engelbrektsskolan” in Örebro, Sweden](https://skolmaten.se/about/calendar/engelbrektsskolan/). The page is in swedish but the subscription link is called ”Kalender” and is located at the bottom of the page. Copy the link for use in your calendar software or just click it, most devices will ask you if you want to subscribe. This is what it will look like on an ipad:

<img src="/Open-Meal/img/Kalender-maltidsinformation-crop.png"><br/>
<img src="/Open-Meal/img/Kalender-maltidsinformation-crop-expanded.png">

## The History

The open meal information project was started by 3 municipalities in Sweden - [Helsingborg](http://www.helsingborg.se/), [Linköping](http://linkoping.se/) and [Örebro](http://www.orebro.se/). The goal was to make sure all municipalities in Sweden shared information about meals as menus in the same way so it would be easier to reuse. The goal was to create open data.

After first trying and failing to find an existing specification for sharing the information they decided to create one of their own. The first version of the specification was very basic and was not published on github.

For the second part of the project the municipality of [Örebro](http://www.orebro.se/) sought and got funds from [VINNOVA](http://vinnova.se/), Swedens innovation agency, to create an expanded specification including the original menu but also ingredients, nutritional values and allergens. The project ran from november 2014 thru june 2015 and involved the municipality och [Örebro](http://www.orebro.se/) with Björn Hagström as project lead, [Dopter AB](http://www.dopter.se/) represented by Andreas Krohn and [Mashie AB](http://www.mashie.se/), the supplier och the system for planing meals at the municipality, represented by Erik Arnwald and Jörgen Brandt.

The goal was to create an open specification that could be used by all suppliers of systems for planning meals and delivering menus and to keep it as small as possible as to not create unnecessary overhead for suppliers. The project delivered a specification for delivering the content as JSON and another as iCalendar for use with electronic calendars.

One motivation for this project was to create a proof-of-concept for solving one of the problems identified by the national coordination of municipal open data headed by [SKR](http://skr.se/) (an organisation for cooperation run by the municipalities) namely that open data published by 290 municipalities in 290 different ways will be very hard to reuse. Since the value of open data is realized in the reuse this aspect is critical in achieving the desired effects (new and better services and transparency in government).

No work was done on the specification until the Swedish project NSÖD (a national project helping municipalities and regions to publish open data in standardized formats). NSÖD created a new version of the specification (3.1) and not long after an updated version 3.2. NSÖD revised the specification and added a lot more structure for ingredients and nutritinal information.

## Licence

All data available via the Open Meal API is published under Creative Commons Zero, which give the consumer of the data full rights to modify the data and use it for commercial purposes without giving attribution.
