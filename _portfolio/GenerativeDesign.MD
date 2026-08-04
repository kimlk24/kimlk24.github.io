---
title: "Generative Electric Skateboard Hanger"
excerpt: "Utilizing Fusion 360 generative design feature to create a sturdy electric skateboard hanger with a motor mount."
weight: 9
header:
  image:
  teaser: /assets/img/New New generative hanger v3 v2.png
gallery:

  - url: /assets/img/GD_I1.jpg
    image_path: assets/img/GD_I1.jpg
  - url: /assets/img/GD_I2.jpg
    image_path: assets/img/GD_I2.jpg
  - url: /assets/img/GD_I3.jpg
    image_path: assets/img/GD_I3.jpg
  - url: /assets/img/GD_I4.jpg
    image_path: assets/img/GD_I4.jpg
  - url: /assets/img/New New generative hanger v3 v2.png
    image_path: assets/img/New New generative hanger v3 v2.png

---

![Current prototype](/assets/img/New New generative hanger v3 v2 2.png)

<!-- TODO Luke: personal project or coursework? add the term/year. -->

*Personal project*

# The problem

An electric skateboard hanger has to hold a rider's full weight and the load from an integrated motor mount, ideally at the lowest weight the geometry allows. Designing that by hand means guessing at material distribution and iterating by trial and error.

# Approach

Fusion 360's generative design tool lets you set preserved geometry, obstacle geometry, and load cases, then generates and ranks candidate designs against a strength or weight target instead of you shaping the part by hand. Generative results often remove material in ways that are impossible to cast or machine, so I chose selective laser sintering to fabricate the part: SLS needs no support structures and can print the complex, organic geometry the algorithm produced.

# Results

* Produced a physical prototype of a generatively optimized hanger with an integrated motor mount

# Tools

Fusion 360 generative design, SLS 3D printing

# CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ed5160b5072cbebf0?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Gallery Images

{% include gallery caption="" %}
