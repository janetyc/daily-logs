---
layout: post
title:  "Send realtime images by OSC"
date:   2013-10-08 22:10:10
categories: reserach
---
In order to submit a short paper in TEI art track, we came up a mini project about playing music by eye gaz. Today I spent 4 hours to finish iPhone app and testing app. I think I spent too much time to solve a scaling issue of digital image processing, but it's a good practice to realize DIP stuff in more detail. I transmited 40x30 pixels to Mac via OSC protocal. I sent each RGB values as 3 integers of each pixel at 30 fps. One of the interesting thing we found is that picture is composed in a different way based on packet lost or delay. The construction process is amazing than we thought before. :)

`@janetyc :-)`

