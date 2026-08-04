---
title: "Automated Blade-Gap Calibration Fixture"
excerpt: "A vision-guided fixture that replaced a manual calibration step, improving precision tenfold and cutting cycle time by 80%."
weight: 1
header:
  image:
  teaser: /assets/img/gap-fixture-in-context.jpg
gallery:
  - url: /assets/img/gap-fixture-in-context.jpg
    image_path: assets/img/gap-fixture-in-context.jpg
    alt: "The calibration fixture on the bench, with the measurement software showing two blade tooth profiles"
---

![The calibration fixture in use](/assets/img/gap-fixture-in-context.jpg)

<!-- TODO Luke: add the year this was built to the context line below. -->

*Product Development Engineer &middot; COCCO Hair Professional &middot; Individual project, deployed with our manufacturing partner*

# The problem

The gap between a trimmer's moving and fixed blade sets determines how closely it cuts. Too tight and it irritates skin; too loose and the cut is imprecise. Getting that gap right out of the box is a persistent problem across the category, and the existing process depended on operator skill and feel, which made it slow and inconsistent from unit to unit.

# Requirements

* Repeatable to a tolerance an order of magnitude tighter than the manual method
* Fast enough to run inline on a production line rather than in a lab
* Operable by a line technician without specialist training
* Built from parts that could be sourced and serviced at the factory

# Approach

Coarse mechanical positioning brings the blade set to a repeatable datum, machine vision measures the gap, and closed-loop motor control drives the adjustment.

Custom software I wrote runs on a small form factor PC, coordinates the sequence, and communicates with an ESP32 that handles motion and I/O. The operator loads a blade set, the fixture measures and adjusts, and the software reports the result.

# Results

* Precision improved from ±0.05 mm to **±0.005 mm**, a **10x** improvement
* Cycle time fell from 2.5 minutes to **30 seconds**, **80% faster**
* Adopted by our manufacturing partner as a standing calibration and QC step

<!-- TODO Luke: add a "What I would change" section with the fixture's honest limitation.
     Interviewers ask this and a real answer beats a polished one.
     Also consider adding a repeatability plot (n repeat measurements on one blade)
     which would be the strongest single artifact on this page. -->

# Tools

Onshape, 3D printing, machine vision, ESP32, Python, closed-loop motor control

{% include gallery caption="" %}
