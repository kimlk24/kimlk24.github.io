---
title: "Programmable Syringe Pump"
excerpt: "DIY programmable syringe pump capable of 1 uL / min flow rate up to 10 mL / min."
weight: 5
header:
  image: /assets/img/syringe pump banner picture.jpg
  teaser: /assets/img/Linear Actuator Assembly v8.png
gallery:
  - image_path: assets/img/Linear Actuator Assembly v8.png

---

*Personal project &middot; 2023*

# CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e817f50c3c936b1b2?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Features

* Programmable flow rate from **1 uL / min to 10 mL / min**, switchable between two syringe sizes.
* Bill of materials **under $150**, against roughly **$375** for the cheapest commercial programmable pump, largely by using 3D printed parts.

# The problem

Syringe pumps are precision instruments used across the medical industry, but the programmable ones are usually expensive. I wanted to build one that was affordable and still held accurate, programmable flow.

# Approach

I designed custom parts to mount the stepper motor, bearings, and hardware around a lead screw carriage sized for two syringe sizes, and rapidly prototyped every part on 3D printers to keep the bill of materials low. Custom firmware drives the stepper motor and reads a set of buttons and LEDs for start, pause, and status, with the flow rate itself set by uploading a new value to the board.

# Results

* Designed, built, and tested a programmable pump holding accurate flow down to **1 uL / min**

# Tools

Fusion 360, 3D printing, Arduino

# Code

The Arduino code can be found [here](https://github.com/kimlk24/kimlk24.github.io/blob/main/Final_Syringe_Pump_Code.ino).

# Rendering

{% include gallery caption="" %}
