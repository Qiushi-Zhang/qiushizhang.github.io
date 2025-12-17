---
title: "Model Predictive Control for Contact-Rich Manipulation (MJPC)"
collection: portfolio
excerpt: "Model predictive control for manipulation tasks involving intermittent contact using physics-based simulation."
---

## Introduction
Contact-rich manipulation tasks involve complex dynamics, discontinuous contacts, and strict safety constraints.
Model Predictive Control (MPC) offers a principled framework for handling these challenges by optimizing actions over a receding horizon.
This project explores the use of **MuJoCo-based MPC (MJPC)** for contact-rich robotic manipulation.

## Methods / Design
I built manipulation environments in MuJoCo and implemented MPC controllers using MJPC.
The controller optimizes control inputs while respecting contact constraints and system dynamics,
allowing the robot to plan force-aware actions in real time.

The system was evaluated in tasks involving sustained contact, surface interaction, and constraint satisfaction.

## Results / Evaluation
The MPC-based controller produced smooth and stable interaction behaviors during contact-heavy tasks.
Compared to reactive control strategies, MJPC improved task robustness and reduced undesired force spikes,
especially during contact transitions.

## Discussion
This work highlights the potential of physics-based MPC for manipulation tasks where contact reasoning is essential.
It also illustrates the importance of accurate modeling and fast optimization for real-time control in contact-rich domains.

## Skills Demonstrated
- Model Predictive Control (MPC)  
- Physics-based simulation (MuJoCo)  
- Contact dynamics and constraint handling  
- Optimization-based control  
