---
title: "Bike Phone Holder"
excerpt: "3D printed phone holder capable of horizontal and vertical placement and adjustable mounting for generic bike handles."
header:
  image:
  teaser: /assets/img/Bike to Phone Adapter v7.png
gallery:
  - url: /assets/img/Pliers final.jpg
    image_path: assets/img/Pliers final.jpg
    alt: "Final CAD of pliers"
  - url: /assets/img/Horizontal Bike mount.jpg
    image_path: assets/img/Horizontal Bike mount.jpg
    alt: "Horizontal orientation"
  - url: /assets/img/Veritcal Phone Bike Mount.jpg
    image_path: assets/img/Veritcal Phone Bike Mount.jpg
    alt: "Vertical orientation"

---

![Rendering of phone bike mount](/assets/img/Bike to Phone Adapter v7.png)

# Features

* **Top-down modeled** phone bike mount capable of supporting the phone in both vertical and horizontal viewing orientations. 
* Able to mount to a variety of bike handle diameters, averaging around 25mm.

# What?

* Top-down modeling is a design modeling approach where each part can be directly created and edited within the same assembly instead of referencing entirely different parts and then updating the assembly
* This allows for quicker editing, easy parameterization, and easy ways to reference other designs within the assembly 
* For this phone mount, we used top-down modeling to quickly design the phone holder around the iPhone 12 mini, and design the entire phone holder assembly in its exact place with respect to the phone and handles. As a result, the model only needed to be printed once since it was modeled in the assembly and everything fit as it should.

**Design**

* For this specific design, I decided to make a 4 stemmed phone holder to secure to each corner of the device. This would allow for enough flexibility to be able to install easily, while maintaining sufficient rigidity and constraints to keep the phone in place. One end of the phone holder has a rectangular cut out for the phone’s raised cameras to allow for a flush fit. To allow for the phone to rotate from horizontal to vertical, I decided to design a simple friction joint where a bolt connected the handle mount to the phone holder via a bolt, and the tightness of the bolt would determine the friction and difficulty to turn the phone from horizontal to vertical and vice versa. Finally, the bike handle mount was designed using a simple clamping mechanism that would be driven with 2 bolts. This would allow the mount to fit on a variety of bike handle thicknesses with an easy way to tighten the mount to stay secure.

**Assembly Instructions**

* To assemble the mount, first take the handle clamp and place it on the desired handle location, ensuring the end of the clamp with the bolt hole is facing towards the rider. 
* Then secure the clamp in place by running a bolt through each hole and tightening it with a nut until it is securely in place
* Align the phone holder to the clamp and use a bolt to join the mount and clamp together until there it is hard to rotate the phone holder
* Finally remove any phone cases on your iPhone 12 mini and snap the phone into place making sure the phone cutout aligns with your cameras.

**Material Choice**

* The material I selected for this project was PETG as it is durable and heat resistant. That way even on hot days, the phone mount will not deform, and it will resist vibrations while riding.

# How?

* Used **CAD software** such as **Fusion 360** to design the bike mount using a top-down modeling method.
* Utilized a 3D printer to fabricate the device.

# Results

* Successfully designed and printed a bike phone holder in 1 iteration though using top-down modeling techniques


# CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e452b6c055c558667?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Images of the mount

{% include gallery caption="" %}

