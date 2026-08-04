---
title: "Water gun alarm clock"
excerpt: "A fun way to get stubborn sleepers out of bed!"
weight: 13
header:
  image:
  teaser: /assets/img/WGP real life.png
gallery:

  - url: /assets/img/WGP real life.png
    image_path: assets/img/WGP real life.png
    alt: "Current iteration"
  - url: /assets/img/WGP p2 cad render.png
    image_path: assets/img/WGP p2 cad render.png
    alt: "3rd iteration"
  - url: /assets/img/WGP p1 cad render.png
    image_path: assets/img/WGP p1 cad render.png
    alt: "2nd iteration"


---

![Current prototype](/assets/img/WGP real life.png)

<!-- TODO Luke: personal project or coursework? add the term/year. -->

*Personal project*

# The problem

Snoozing through an alarm is easy when the only consequence is sound. The goal was an alarm clock that makes ignoring it a much worse option, by aiming a water gun at whoever is still in bed.

# Approach

I designed a 2-axis pan-tilt mechanism with design-for-manufacture and assembly in mind, then wrote firmware integrating stepper motors, servos, an LCD screen, a speaker, and DC motors to control it. I rapidly prototyped across three iterations to land on the most reliable mechanism.

# Results

* Built physical prototypes across **three iterations**, integrating the mechanism with a water gun, light, sounder, and screen

# Tools

SolidWorks, Arduino, 3D printing, laser cutting

# Future

* Integrate camera and computer vision to track sleeping faces so that water is inevitable

{% include gallery caption="" %}
