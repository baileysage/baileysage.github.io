---
layout: post
title: "Barn Quilt"
categories: [electronics, art, led_project]
date: 2021-12-02 18:00
---

I would someday like to build a full 8' x 8' square barn quilt with programmable LEDs. 
But that's several tens of thousands of dollars and a lot of skills I do not have yet. And there are a lot of pieces to figure out, such as the design interface, that can be done without the full hardware setup. 
So when I saw [this Half Square Triangles instructable](https://www.instructables.com/Half-Square-Triangles-LED-Art/) it looked like a good place to start! 

I got a little worried when I started printing it. The baseplate takes up almost the entire printable area of the printer I have access to.

![baseplate print started]({{ site.url }}/assets/images/barn_quilt_print_started.jpg)

The divider is white to reflect more light within the panel. Hoping light doesn't leak _through_ the plastic, but if it does, I'll print it again in a darker color. 

![divider printing]({{ site.url }}/assets/images/barn_quilt_divider_printing.jpg)

Got the LED strips placed and have started soldering them up. I've been sneaking in 5-10 minutes in where I can, so I haven't quite finished.

![lights placed]({{ site.url }}/assets/images/barn_quilt_lights_placed.jpg)

Have pulled in the demos from the instructable and started porting them to work on an ESP32. I eventually want to add a web based control panel, similar to [Ben Hencke's Pixelblaze](https://www.bhencke.com/pixelblaze), to draw the quilt patterns. But first things first; get the lights turned on! 