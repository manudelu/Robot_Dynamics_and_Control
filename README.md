Robot Dynamics and Control 🦾
================================

This repository contains MATLAB and Simulink code and resources that demonstrate the implementation of Gravity Compensation Algorithm, Recursive Newton-Euler Algorithm (RNEA), PD Control and Computed Torque Control for different robotic arm configurations, including 1R, 2R, 2R-NP, 3R, and RP arms. Each arm's modeling and control are detailed in their respective sections.

Before running the simulations, ensure that you have the "Robotics Systems Toolbox" and "Simscape Multibody" MATLAB Add-On installed.

Gravity Compensation Algorithm 
--------------------------------
The Gravity Compensation Algorithm is fundamental to ensure the stability of robotic arms. It counters the gravitational forces acting on the arm, allowing it to maintain its posture and prevent unwanted movement when no control input is applied.

Recursive Newton-Euler Algorithm (RNEA)
----------------------------

The Recursive Newton-Euler Algorithm is a dynamic simulation and control technique used to calculate joint torques needed to achieve a desired trajectory or configuration. This algorithm consists of two crucial steps: the forward recursive step for calculating dynamic quantities and the backward recursive step for determining joint torques.

PD Control (Proportional-Derivative Control)
--------------------------

PD control is a widely used feedback control technique for robotic arms. It generates control signals based on the error between the desired and actual position, facilitating accurate position control while minimizing oscillations.

Computed Torque Control
------------------------

Computed Torque Control, or inverse dynamics control, is a precise control strategy that considers the dynamics of the robotic arm. It calculates the joint torques required to follow a desired trajectory while compensating for inertial and Coriolis forces.


