---
title: "Multi Material Pliers"
excerpt: "Multi material print-in-place pliers made of PLA and TPU to pick and place through hole resistors."
weight: 6
header:
  image:
  teaser: /assets/img/Pliers render.jpg
gallery:
  - url: /assets/img/Pliers final.jpg
    image_path: assets/img/Pliers final.jpg
    alt: "Final CAD of pliers"
  - url: /assets/img/Pliers final top section view2.jpg
    image_path: assets/img/Pliers final top section view2.jpg
    alt: "3/4 section view of pliers"
  - url: /assets/img/Pliers final bottom section view.jpg
    image_path: assets/img/Pliers final bottom section view.jpg
    alt: "1/2 section view of pliers"

---

![Rendering of the multi material pliers](/assets/img/Pliers render.jpg)

<!-- TODO Luke: personal project or coursework? add the term/year. -->

*Personal project*

# Features

* **Print-in-place** multi material design requiring **zero assembly** after printing, using design-for-additive techniques to add a fully enclosed skeleton and TPU handle grips.
* Capable of picking and placing through hole resistors and being used as a general set of low strength pliers.

# The problem

Most everyday tools, like a classic pair of needle nose pliers, combine a rigid mechanism with a rubberized grip — two materials that normally have to be assembled together after they're made. Print-in-place multi-material printing can produce that same combination as one part straight off the bed, with no assembly step at all, if the materials are chosen carefully. The goal here was a print-in-place pliers in PLA and TPU that returns to the open position on its own when released.

# Approach

Successful multi-material prints need materials with compatible cooling and shrinkage behavior, similar surface energy, and similar intermolecular forces so the layers actually bond instead of delaminating. I chose PLA and TPU for that compatibility, then designed the pliers to fully enclose a PLA skeleton inside a TPU handle grip — a construction that is straightforward in layer-by-layer fabrication but close to impossible with conventional manufacturing.

# Results

* Designed and printed a set of pliers usable **straight off the print bed with no assembly**, able to pick and place through hole resistors

# Tools

Fusion 360, multi material 3D printing (PLA and TPU)

# Design Specifications

Plier Jaw Width: 4 mm
Plier Jaw Length: 24 mm
Handle Width: 62 mm

# Demonstration

![Rendering of the multi material pliers](/assets/img/PliersGIF.GIF)

# CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e97c9bc81b8c733fb?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# CAD and section views of pliers

{% include gallery caption="" %}
