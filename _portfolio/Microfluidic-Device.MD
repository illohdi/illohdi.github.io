---
title: "Microfluidic Device"
excerpt: "Designing a chip that homogenously mixes to streams of material together"
header:
  image: assets/img/By_science_photo-1.webp
  teaser: 
---

Introduction to Microfluidic (µFluidic) Devices

Microfluidic devices, which control and manipulate fluids on a microscopic scale, are widely used in biomedical applications like diagnostics and cell culture. A common application requiring **homogeneous mixing** in these devices is in chemical and biological assays, where precise mixing is essential to ensure consistent reactions and accurate results. However, mixing in microfluidics can be challenging due to the **dominance of laminar flow** at the microscale. This flow pattern results in fluids moving in parallel layers, with minimal natural intermixing, making it necessary to design structures within the device that encourage mixing.

Design Rationale: Mixing Geometries

**Mixing Geometries**: In microfluidics, effective mixing relies heavily on the design of the device’s internal channels. Geometries such as **zig-zag or serpentine channels** increase the contact surface and path length for fluid flows, promoting mixing through diffusion. These configurations create the necessary flow disruptions to achieve more uniform mixing, countering the laminar flow that would otherwise limit fluid interaction. The design that I utilized fattempted to take advantage of angled turns to create turbulent flow and mix the two substances together. The design would have been more efficient if herringbone features were added as well.

### Why Parylene Coating is Necessary for Resin-Printed Molds

Resin-printed molds used in microfluidic devices must be coated with **parylene**, a biocompatible, non-stick layer, prior to casting with PDMS (polydimethylsiloxane). This step is essential for two reasons:
  - **Biocompatibility**: Uncoated resin molds can leach toxic monomers, posing a risk to biological samples like cells. Parylene, a commonly used medical-grade polymer, forms a protective barrier that prevents these contaminants from affecting the final device.
  - **Demolding Efficiency**: Parylene coating also ensures that PDMS does not stick to the mold during curing, allowing for clean demolding and preserving the integrity of intricate microfeatures. 

*Layman’s Explanation*: Imagine making a jelly mold but with materials that could contaminate the jelly or make it impossible to remove cleanly. Parylene creates a thin, safe coating so the jelly (or in this case, PDMS) keeps its shape, remains uncontaminated, and releases smoothly from the mold.

### Hypothetical Applications of a Microfluidic Mixer

Microfluidic mixers are instrumental in applications that require precise and consistent fluid mixing. Hypothetical applications include:
  - **Diagnostic Assays**: In mixing reagents for rapid diagnostic tests, especially those sensitive to concentration variations.
  - **Drug Testing**: Homogeneous mixing is essential when testing new drugs or chemicals to ensure accurate interactions within controlled microenvironments.
  - **Cell Culturing**: In situations where nutrient gradients or chemical gradients must be established uniformly to observe cell behavior or response in a controlled environment.

### Step-by-Step Instructions: From 3D-Printed Mold to Final Device

To fabricate a microfluidic device, follow these steps:

1. **Print and Cure the Mold**:
   - Design the mold with CAD software, print it using a high-resolution 3D printer, and post-process by washing with isopropyl alcohol and curing under UV light.

2. **Parylene Coating**:
   - Coat the mold with parylene to create a non-stick, biocompatible surface. This coating process involves sublimating parylene dimers, converting them to monomers, and polymerizing them on the mold’s surface in a thin, uniform layer.

3. **Casting PDMS**:
   - Mix the PDMS elastomer with curing agent (typically a 10:1 ratio), pour it over the parylene-coated mold, degas to remove air bubbles, and cure in an oven at 80 °C for 3 hours. Once cured, demold the PDMS device carefully.

4. **Plasma Bonding to a Glass Slide**:
   - Plasma-treat the PDMS device and a glass slide to activate their surfaces, then press them together to bond. This step finalizes the device, creating a sealed environment for fluid flow.

---

CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a440333171449b7c82?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


