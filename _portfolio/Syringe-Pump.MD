---
title: "Large Format 3D Printer"
excerpt: "A 1 kg/hr pellet extruder and 1 cubic meter build envelope for printing furniture."
header:
  image: /assets/img/LF3DP-Banner-2.jpg
  teaser: /assets/img/Large-Format-3D-Printer-Thumbnail.png
gallery:
  - image_path: assets/img/Slide-3.png
  - image_path: assets/img/Slide-2.png
  - image_path: assets/img/Slide-4.png
   
---

# Features

* **Massive Print Area: 1140 x 1200 x 1100 mm.** With a build envelop just shy of 4 feet in all dimensions, the LF3DP is capable of printing furniture and other large objects.
* **High Volumetric Output Extruder: 1 kg/hr - 450 C.** This printer come standard with a MDPH2 extruder by Massive Dimension, which can extrude at a rate of 1 kg/hr. Unlike typical filament extruders, the MDPH2 uses a screw to convey and liquify plastic pellets before the molten material is pushed out of a large nozzle (1 to 5 mm extrusion diameter). Please note: This printer can also be configured for other high flow rate extruders, such as the Typhoon and Pulsar by Dyze Design.
* **Affordable Pellet Feedstock** Pellets are the cheapest form of feedstock for any plastic-based manufacturing process. Save 50-75% of material costs by using pellets instead of spools of filament. Concentrated colorant can be added to the virgin material to achieve any color in the rainbow without requiring large amounts of storage. Recyled material can also be used for sustainable material printing.

# CAD Model
<iframe src="https://myhub.autodesk360.com/ue2df0af5/shares/public/SH35dfcQT936092f0e437224cd558fdcdc2f?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="Large Format 3D Printer Gallery" %}




---
title: "Syringe Pump"
excerpt: "This syringe pump provides precise flow rate control, is compatible with syringes of different diameters, and is driven through a stepper motor."
header:
  image: assets/img/Screenshot 2024-09-03 040346.png
  teaser: assets/img/Screenshot 2024-09-03 040359.png


|Parts|Off the Shelf|3D Printed|
|-----|-------------|----------|
|     |Button Switch| Carriage |
|     |BreadBoard|  | End Support Nozzle End|
|     |Coupler| End Support Plunger End|
|     |Ball Bearing| End Supports |
|     |LED lights| Motor Mount |
|     |Linear Bearing|     |
|     |Lead Screw|     |
|     |Linear Rod|      |
|     |Bolt||
|     |Tee Nut|  |
|     |Motor|  |
|     |Potentiometer|  |
|     |V-Slot|  |
|     |Arduino Uno|  |
|     |Boton|  |
|     |RQ-65|  |

---

#CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a4a2f3d997ef4feef4?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


#Instructions for Operation
- Flash the arduino with the SyringePumpProgram.ino file if not already
- Turn on the power supply by plugging it into a 120 V outlet
- Push the latching button to active the syringe pump, the led on the front board will turn green to indicate that it’s on
- Watch the syringe pump pump at a specific flow rate (mL/m)
- You can pause the syringe pump by clicking on the latching button again and the led will turn yellow to indicate that the syringe pump is paused
- When the syringe is empty, it’ll hit the limit switch. The limit switch will stop the syringe and make the led red to inform you that it’s empty.
- Push the latching to turn off the syringe pump
- Reset the syringe pump and do it all over again
- If you want to change the flow rate go in the .ino file and change the flowRate global variable or you can manually change the flow rate with the potentiometer on the front


