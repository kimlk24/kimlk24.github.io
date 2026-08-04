---
title: "Micro Fluidic Mixing Device"
excerpt: "Fluidic device which mixes two fluids at a micro scale."
weight: 7
header:
  image:
  teaser: /assets/img/uFluidic Device Render.png
gallery:
  - url: /assets/img/uFluidicMixing.jpg
    image_path: assets/img/uFluidicMixing.jpg
    alt: "uFluidic Mold and Device"
  - url: /assets/img/RotateduFluidicMolds.jpg
    image_path: assets/img/RotateduFluidicMolds.jpg
    alt: "uFluidic Mold and Device"
---

# CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e954320b5999ab871?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

<!-- TODO Luke: coursework or personal project? add the term/year. -->

# Features

* Dual mixing channels with a total fluid capacity of **2.25 mL**, keeping the sample volume required for a test very small.

# The problem

Fluidic testing, like a blood panel, often needs expensive antibodies and a full vial of sample. A device that mixes fluids reliably at the microliter scale, using only a drop of sample, makes that kind of testing cheaper and far more accessible. The catch is that at this scale, the Reynolds number is too low for turbulent mixing to happen on its own, so the device has to rely on diffusive mixing instead.

# Approach

Because the part is cast in PDMS, I designed the mold rather than the device itself, sizing every channel to **0.5 mm wide by 0.4 mm tall** to stay within both the resin printer's resolution and a printable width-to-height ratio. The channels run in a snake-like pattern on both mixing sections to maximize path length and surface area for diffusion. One section layers narrower horizontal channels to increase surface area further; the other uses small inclined ramps that create chaotic flow to blend the two liquids. After printing the mold on a resin printer, I coated it with parylene, cast PDMS into it, and plasma-bonded a glass slide with tube adapters to complete the device.

# Results

* Designed and cast a working microfluidic device from researched mixing techniques
* The device fully mixed two liquids within about **one fifth of the mixer's total length**

# Tools

Fusion 360, resin 3D printing, PDMS casting, parylene coating, plasma bonding

# Video of the device in use

<iframe width="560" height="315" src="https://www.youtube.com/embed/bpBCI8SE83E?si=v4qpA5a6pJV7EiFj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# 3D Printed uFluidic Mold

{% include gallery caption="" %}
