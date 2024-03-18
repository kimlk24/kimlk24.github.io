---
title: "Micro Fluidic Mixing Device"
excerpt: "Fluidic device which mixes two fluids at a micro scale."
header:
  Image: 
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
 
# Features

* **Dual mixing channels.** Total fluid capacity 2.25 mL which allows for small amounts of fluids required to test.

# What?

* When testing blood or other fluids, expensive antibodies are often required. These antibodies can be as much as 4500x more expensive than gold. Additionally, when conducting blood testing, only need one drop of blood versus an entire vial can make blood tests more accessible and easy to collect.
* As a result, a microfluidic device which can mix multiple fluids to conduct testing is a useful technology to reduce costs and increase accessibility to fluidic testing.
* However, at a small Reynold's number, turbulent mixing does not occur. Due to the small scale of this fluid mixing, the Reynold's number is very small and therefore we cannot rely on turbulent mixing to mix the fluids at a micro scale. Instead, we must rely on diffusive species mixing to achieve the desired fluidic mixing.
* This microfluidic device is designed to mix fluids at a micro scale while only requiring as low as 2.25 mL of fluid.

# How?

* Used **CAD software** such as **Fusion 360** to design a custom mold to make a micro fluidic device.
* **Researched** and implemented mixing techniques to design a fluid mixing device
* Utilized a **Resin 3D printer** to print the mold to create the small details of the microfluidic device.

# Mixing Techniques


As shown in the gallery at the bottom of this page, the pathways in the microfluidic device are arranged in a snake like pattern, to make them longer. This makes the liquid travel a greater distance, increasing the surface area for diffusion, causing it to mix better. On the right side of the device, there are two sections arranged in this snake pattern. Each snake pathway is 0.5 mm wide and 0.4 mm tall. This size ensures that the width-to-height ratio stays within the recommended range for successful micro resin printing. It also provides enough space for fluids to flow and for creating various pathways while still being suitable for the resolution of the resin printer. One section has narrower horizontal channels, which layer the fluidic channels and therefore increase the surface area for better mixing. The other section has small ramps called inclined mixers. These mixers help create chaotic movement in the fluid, effectively blending the two liquids together.

# Results

* Successfully designed and created a microfluidic devices based off of researched mixing techniques
* The microfluidic device successfully mixed 2 liquids within about 1/5th of the total length of the mixer.

# How to create a microfluidic device

To create a microfluidic device, use the following general steps as a guide
* First you must design the mold. Do this using a CAD software and designing the negative of your desired pathway.
* Then print your mold on a high resolution resin printer and cure the model
* Coat the mold with parylene to prepare for molding
* Cast PDMS to create your device
* Finally plasma bond a glass slide and insert liquid tube adapters


# 3D Printed uFluidic Mold

{% include gallery caption="" %}
