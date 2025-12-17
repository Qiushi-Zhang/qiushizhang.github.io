---
title: "PropHand: Proprioceptive Dexterous Robotic Hand"
collection: portfolio
excerpt: "A torque-controlled, tendon-driven robotic hand for contact-rich manipulation using proprioceptive force estimation."
---

## Introduction
Robotic manipulation in unstructured environments requires precise regulation of contact forces.
However, most existing robotic hands rely on expensive or fragile tactile sensors.
This project explores **proprioceptive force estimation** as an alternative sensing modality
for contact-rich manipulation.

## Methods / Design
I designed and built a **fully actuated, tendon-driven robotic hand** powered by custom
BLDC actuators and embedded motor controllers.
Joint torques are estimated using motor current sensing and dynamic models,
enabling direct **torque and impedance control** without dedicated force sensors.

My responsibilities included mechanical design, actuator integration,
embedded firmware development, and control implementation.

## Results / Evaluation
The system demonstrated stable force regulation during contact-intensive tasks such as
surface following and tool interaction.
Compared to position-only control, the proprioceptive force-based controller
reduced force tracking error and improved interaction stability.

## Discussion
This project shows that proprioceptive sensing can provide a scalable and robust
alternative to tactile sensing for many manipulation tasks,
simplifying hardware design while preserving force awareness.

## Skills Demonstrated
- Torque and impedance control  
- Proprioceptive force estimation  
- Embedded motor control (STM32, CAN)  
- Mechanical design and system integration  
