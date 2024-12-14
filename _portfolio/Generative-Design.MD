---
title: "Generative Design"
excerpt: "Creating a lightweight truck hanger with an integrated motor mount for a brushless DC motor"
header:
  image: assets/img/reverse-kingpin-trucks.jpg
  teaser: 
---

# Discussion on Generative Design and Powder Bed Fusion

## The Unique Pairing of Powder Bed Fusion and Generative Design

Generative design and powder bed fusion (PBF) represent a transformative pairing in modern manufacturing, enabling the creation of highly optimized components with complex geometries. Generative design leverages advanced computational algorithms to explore design possibilities based on constraints like material, weight, and load requirements. Meanwhile, PBF, a form of additive manufacturing, realizes these designs by precisely fusing powdered material layer by layer.

In the **automotive industry**, generative design and PBF have significantly impacted lightweighting and part consolidation. For example, General Motors developed a seat bracket that consolidated eight separate components into one part, reducing weight by 40% while enhancing strength. PBF’s ability to fabricate lattice-like geometry was key to this innovation. This synergy highlights how generative design creates the concept, and PBF brings it to life.

## Specific Commercial Example

In the **aerospace industry**, Airbus used generative design and PBF to redesign a partition for its A320 aircraft. The partition, which separates passenger and crew areas, underwent a generative design process to minimize weight while maintaining structural integrity. The new design reduced weight by 45% compared to its traditional counterpart. PBF enabled the integration of complex lattice structures, which would have been impossible with conventional methods. This weight reduction improved fuel efficiency and allowed for additional payload, showcasing the commercial and environmental benefits of this technology.

## Importance of Proper Load Cases and Structural Constraints

Accurate load cases are essential in generative design to ensure the final part performs under real-world conditions. For this project, forces applied to the model were:

- **Vertical load**: Representing the rider’s weight, distributed across the axle.
- **Impact load**: Simulating sudden forces from jumps or collisions.
- **Lateral forces**: Accounting for bending stresses during turns.
- **Motor torque**: Representing the twisting force exerted by the motor.

Structural constraints were placed at critical points, such as the axle hole and kingpin interface, ensuring the hanger remains fixed during operation. These constraints define how loads transfer through the part, ensuring functional requirements are met while minimizing unnecessary material.

## Comparison Between Nylon and Aluminum Outcomes

The outcomes for Nylon 12 and ALSi10Mg (aluminum alloy) differ significantly due to their material properties:

- **Nylon 12**:
  - Lightweight and flexible.
  - Suitable for low-stress applications but less durable under heavy loads.
  - Ideal for prototyping due to cost-effectiveness.
- **ALSi10Mg**:
  - Stronger and more rigid, making it better suited for high-stress applications.
  - Higher density than Nylon 12, resulting in a heavier part.
  - More resistant to fatigue and wear, suitable for long-term use.

While Nylon 12 offers cost savings and flexibility, ALSi10Mg is preferable for applications requiring strength and durability, such as supporting motor torque and impact forces.

## Critique of Generative Design

Generative design is a powerful tool, but it is not without limitations:

- **Benefits**:
  - Produces innovative solutions that maximize material efficiency and performance.
  - Reduces design time by exploring multiple options simultaneously.
  - Ideal for part consolidation, reducing assembly costs and failure points.
- **Drawbacks**:
  - Computationally intensive, requiring significant time and resources for complex designs.
  - Designs often result in organic shapes that are difficult to manufacture using traditional methods.
  - Highly dependent on accurate input parameters; incorrect constraints or loads can lead to impractical designs.

Generative design is most useful in industries where weight and efficiency are critical, such as aerospace, automotive, and medical device manufacturing. It is less practical for simple parts or applications with limited design freedom due to cost constraints.

## Conclusion

The integration of generative design and powder bed fusion is revolutionizing manufacturing by enabling lightweight, high-performance components with unprecedented complexity. While generative design has its challenges, its ability to optimize material usage and enhance functionality makes it a valuable tool in advancing engineering solutions. Proper load case application and material selection remain critical to achieving the best outcomes, ensuring the final product meets performance and manufacturability requirements.

![Motor and Wheel Gear Attachment](./assets/img/IMG_8921.jpg)
