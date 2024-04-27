---
title: "Generative Electric Skateboard Hanger"
excerpt: "Utilizing Fusion 360 generative design feature to create a sturdy electric skateboard hanger with a motor mount."
header:
  image:
  teaser: /assets/img/New New generative hanger v3 v2.png
gallery:

  - url: /assets/img/GD_I1.jpg
    image_path: assets/img/GD_I1.jpg
  - url: /assets/img/GD_I2.jpg
    image_path: assets/img/GD_I2.jpg
  - url: /assets/img/GD_I4.jpg
    image_path: assets/img/GD_I4.jpg
  - url: /assets/img/New New generative hanger v3 v2.png
    image_path: assets/img/New New generative hanger v3 v2.png

---

![Current prototype](/assets/img/New New generative hanger v3 v2 2.png)

# What?

* Generative design is when a computer creates a design based off of a set of starting parameters to optimize the design for strength or weight. Fusion 360 has a built in generative design feature where you can set preserved geometry and obstacle geometry. Then you can set different load cases that the design might face. In the case for this project, an example load case would be the weight of a human on the skateboard. Then you can set the desired outcome, normally it is optimizing strength given a weight, or optimizing weight given a strength constraint. One downside of generative design is that the computer can take away material in unique areas that make it extremely difficult or impossible to manufacture with normal methods. This is because normally as the computer is generating a design, it is slowly taking away material from unnecessary places which can cause holes. When there are holes in the design, normally it is impossible to cast a mold, and it becomes extremely difficult to use subtractive methods. As a result, additive manufacturing techniques are ideal for manufacturing generative designs. 
* Furthermore, in most additive manufacturing techniques like FDM or resin printing, there needs to be supports in order to create complex designs. However, selective laser sintering, or SLS, printing is extremely useful in fabricating generative designs as it needs no supports and can print complex geometry. 
* Generative design is extremely useful in optimizing geometries to be as light as possible which is useful for many industries, especially in the high performance automotive or aerospace industry where power to weight ratio is important. Generative design allows a user to generate a multitude of optimized designs much quicker than a person could design on their own.
* If you think of high performing automotive industries like Formula 1 where weight reduction is incredibly important, you can imagine how valuable generative designs which provide equal strength but with less weight can provide significant advantages to a team. One example of an industry currently using generative designs is Bugatti, which used generative designs to create lightweight but sufficiently strong brake calipers to optimize their car design.

# How?

* Used **Fusion 360** to set u design parameters and generate the design
* Used an **SLS printer** to fabricate the part

# Results

* Utilized **additive manufacturing** processes such as SLS printing to create physical prototype

# CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ed5160b5072cbebf0?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Gallery Images

{% include gallery caption="" %}
