---
title: "Hand Exoskeleton for Force-Aware Teleoperation and Demonstration"
collection: portfolio
excerpt: "A torque-controlled wearable hand exoskeleton for capturing force-rich human demonstrations in manipulation tasks."
---

## Introduction
Learning contact-rich manipulation policies from human demonstrations requires more than kinematic trajectories.
Interaction forces and compliance play a critical role in task success, yet are often missing from standard demonstration pipelines.
This project addresses this gap by developing a **force-aware hand exoskeleton** for teleoperation and demonstration capture.

## Methods / Design
I designed a **wearable hand exoskeleton** with backdrivable, torque-controlled joints that align with human finger motion.
The system supports bilateral control, allowing forces encountered by a remote robotic hand to be reflected back to the user.

The exoskeleton is integrated with custom motor controllers and supports impedance and torque control modes,
enabling safe and intuitive interaction.

## Results / Evaluation
The system achieved stable bilateral coupling during teleoperation tasks involving contact and surface interaction.
Compared to position-only teleoperation, force feedback improved task precision and reduced excessive contact forces,
resulting in higher-quality demonstration data.

## Discussion
This project demonstrates the importance of **hardware interfaces that capture both motion and force**
for learning contact-rich manipulation.
The exoskeleton provides a practical platform for collecting force-informed demonstrations
that can improve downstream learning and control algorithms.

## Skills Demonstrated
- Haptic and bilateral control  
- Human–robot interaction  
- Wearable robotic system design  
- Embedded torque control  
