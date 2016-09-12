---
layout: post
title:  "Some screenshots"
date:   2016-09-12 00:00:00
author: Massimiliano Bernabé
categories: development
tags:	screenshots
cover:  "/assets/app_v0.jpg"
---

We are still alive, we are developing the first patterns in user experience.
Now we can share first screenshots of the new application.



# The map

![Map fragment]({{ site.url }}/assets/app_v0_map.png)

Powered by [Osmdroid](https://github.com/osmdroid/osmdroid) library the user experience is amazing. You can zoom and pan at light speed.
Moreover we have implemented our technique "[Identification tiles](http://develost.com/blog/2016/08/25/identification-tiles)" in this application natively boosting
the performance for identification on multiple layers.

We added the current position of the user on the map, as suggested by some user.

The style of the map is taken from "OpenStreetMap for the dyslexic" our previous work, we will modify it in the future.

# Information about a location

![Identification]({{ site.url }}/assets/app_v0_location_info.png)

When the user taps on the map, an identification occurs. We made the process of identification as fast as possible, to invite the user to identify as many locations he wants.
The map becomes proactive and becomes funny to identify items on the map.  

# An about is always needed

![About]({{ site.url }}/assets/app_v0_about.png)

When the application starts the about is shown. We planned here to put some news, but for now is ok to present the "boring about" since the project is still the the beginning.
