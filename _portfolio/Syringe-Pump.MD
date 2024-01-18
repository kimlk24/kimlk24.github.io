---
title: "Programmable Syringe Pump"
excerpt: "DIY programmable syringe pump capable of 1 uL / min flow rate up to 10 mL / min."
header:
  image: 
  teaser: /assets/img/Linear Actuator Assembly v8.png
gallery:
  image-path:/assets/img/syringe pump banner picture.jpg
---

# CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e817f50c3c936b1b2?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
 
# Features

* **Programmable flow rate.** Capable of flow rates as low as 1 uL / min to 10 mL / min and able to switch between two different syringe pump sizes.
* **Affordable bill of materials.** Programmable syringe pumps start at around $375, and this syringe pump has a cost under $150. That makes this syringe pump extremely affordable especially due to the use of 3D printed parts.

# What?

* Syringe pumps are precision instruments used in the medical industry but are often nor programmable and expensive
* The goal of this project is to create a programmable, affordable, and accurate syringe pump

# How?

* Used **CAD software** such as **Fusion 360** to design custom parts to fit stepper motors, bearings, mounting hardware, and various sized syringe pumps
* **Rapidly prototyped** custom parts by utilizing **3D printers**
* **Programmed** and **wired** a stepper motor, LEDs, a switch, power supply, and buttons using an **Arduino** using custom code

# Results

* Successfully designed, built, and tested a programmable syringe pump device capable of flow rates as low as 1 uL / min with high accuracy.

# Materials

## Off the shelf parts

| Part      | Quantity |
| :---        | :---        | 
| 20x40x300 (mm) Aluminum Extrusion | 1 | 
| Linear Bearing | 1 |
| Flanged Ball Bearings | 2 |
| NEMA 17 Stepper Motor | 1 |
| 5 mm to 8 mm Coupler | 1 |
| 2 mm Pitch Lead Screw | 1 |
| 8 mm Collar | 2 |
| 8 x 200 mm Linear Rod | 1 |
| M5 T-Nut | 6 |
| Lead Screw Flange | 1 |
| 8 mm Linear Rod Clamp | 2 |
| M4-0.7 x 3 | 2 |
| M5-0.5 x 10 mm | 4 |
| M5-0.8 x 8 mm | 6 |
| M3-0.5 x 6 mm | 4 |
| M4-0.7 x 3 | 2 |
| M3-0.5 x 0.8 | 2 |
| Power supply (12v and 24v) | 1 
| LED | 3 |
| End switch | 1 |
| Button | 3 |

## 3D printed parts

| Part      | Quantity |
| :---        | :---        | 
| Carriage | 1 |
| Motor Mounting Plate | 1 |
| Linear Support with Syringe Pump Accommodations | 2 |

# Code
The Arduino code can be found [here](https://github.com/kimlk24/kimlk24.github.io/blob/main/Final_Syringe_Pump_Code.ino).
Or you can directly download it [here](/Final_Syringe_Pump_Code.ino).

# How to operate

To operate, first plug in to the USB B port and upload the Arduino code with the desired flow rate. Then plug in the device and click the on button so that a yellow light appears. To start the flow, click the start/pause button and the LED should become green. You can pause the rate of flow using the same start/pause button and when paused, the light will become yellow. Once the syringe pump is fully depressed, the light will turn red, and the motor will turn off. To reset, unplug the device and manually retract it by turning the lead screw. Alternatively, you can upload a new flow rate with a negative sign and use the start/pause button to retract the syringe pump.

{% include gallery caption="" %}
