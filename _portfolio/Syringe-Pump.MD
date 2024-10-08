---
title: "Syringe Pump"
excerpt: "This syringe pump provides precise flow rate control, is compatible with syringes of different diameters, and is driven through a stepper motor."
header:
  image: assets/img/Screenshot 2024-09-03 040346.png
  teaser: assets/img/Screenshot 2024-09-03 040359.png
---

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


