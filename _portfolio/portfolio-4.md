---
title: "Proprioceptive Force Estimation for Contact-Rich Manipulation"
collection: portfolio
excerpt: "An algorithmic framework for estimating external contact forces using motor torque sensing and system dynamics."
---

## Introduction
Reliable force estimation is critical for contact-rich manipulation, yet direct force sensing is often impractical
due to cost, fragility, or integration complexity.
This project focuses on developing **proprioceptive force estimation algorithms**
that infer external interaction forces from motor and joint-level measurements.

## Methods / Design
I developed force estimation algorithms based on motor torque sensing, joint dynamics, and system modeling.
By combining measured motor currents with dynamic models,
the algorithm estimates external contact forces without requiring dedicated force or tactile sensors.

The estimator is designed to operate in real time and integrate seamlessly with torque and impedance controllers.

## Results / Evaluation
The proposed estimator provided accurate force estimates during contact interactions,
enabling stable force and impedance control.
Experimental results showed that the estimated forces closely tracked ground-truth interaction trends,
supporting reliable contact detection and regulation.

## Discussion
This project demonstrates that proprioceptive sensing can serve as a powerful alternative to explicit force sensors.
Such approaches reduce hardware complexity while enabling force-aware control,
making them attractive for scalable robotic manipulation systems.

## Skills Demonstrated
- Proprioceptive force estimation  
- Robot dynamics and modeling  
- Torque and impedance control  
- Real-time algorithm design  
