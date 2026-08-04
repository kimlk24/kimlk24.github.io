---
title: "Amazon Robotics Work in Progress Buffer"
excerpt: "A proof of concept device which aims to temporarily organize, store, and reintroduce packages to allow a robotic arm to continue to autonomously sort packages."
weight: 4
header:
  image:
  teaser: /assets/img/AR teaser.png
gallery:

  - url: /assets/img/AR initial prototype.png
    image_path: assets/img/AR initial prototype.png
    alt: "Initial prototype idea"
  - url: /assets/img/AR prototype.png
    image_path: assets/img/AR prototype.png
    alt: "Main prototype"
  - url: /assets/img/AR CV.png
    image_path: assets/img/AR CV.png
    alt: "Computer Vision"
  - url: /assets/img/AR Main assembly WIP buffer with camera stand.png
    image_path: assets/img/AR Main assembly WIP buffer with camera stand.png
    alt: "Rendering of Final Prototype"

---

![CAD Rendering](/assets/img/AR Main assembly WIP buffer with camera stand.png)

*Senior capstone, team project for Amazon Robotics &middot; Vanderbilt University &middot; September 2023 &ndash; May 2024*

# The problem

Cardinal, Amazon Robotics' pick-and-place sorter, routes a percentage of the packages it handles into a manual exception cart whenever it cannot confidently place one. Under heavy load, that cart backs up faster than a person can clear it, so Cardinal effectively idles while it waits on manual sorting to catch up.

# Requirements

* Buffer exception packages temporarily without permanently removing them from the sort
* Reintroduce buffered packages automatically once Cardinal has capacity again
* Run standalone hardware and software, sponsor-facing deliverable within a two-semester capstone

# Approach

Our team designed a four-conveyor buffer arranged in a loop: exception packages ride the loop instead of a manual cart, and get released back to Cardinal as slots open up. I designed the custom adapters, frames, and belt assemblies, rapidly prototyping every part on 3D printers and laser cutters and iterating from an early concept model up to the final assembly shown below. I also programmed and wired the stepper motors driving the conveyors and integrated the computer vision that identifies and tracks packages as they cycle through the loop.

# Results

* Built and tested a working 4-conveyor buffer that organizes packages in a closed loop
* Projected to reduce manual exception handling **75%**
* Presented a poster and delivered a white paper to Amazon Robotics

# Tools

Onshape, 3D printing, laser cutting, Arduino, Python, computer vision

# CAD Model

<iframe src="https://vanderbilt289.autodesk360.com/shares/public/SHd38bfQT1fb47330c999c58300a8ae1cadb?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="" %}
