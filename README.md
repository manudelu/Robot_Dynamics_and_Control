Robot Dynamics and Control
================================
Implementation of Gravity Compensation Algorithm, Recursive Newton-Euler Algorithm (RNEA), PD Control and Computed Torque Control of 1R, 2R, 2R-NP, 3R and RP Robotic Arms on Simulink
-------------------------------

`Gravity Compensation Algorithm`

*`Aim`: The Gravity Compensation Algorithm is used to counteract the gravitational forces acting on a robotic arm, allowing it to maintain a desired position in the absence of any control input.
*`How it works`: It calculates and applies torques to counteract the effects of gravity. These torques ensure that the arm doesn't fall due to gravitational forces when no other control inputs are applied. This is particularly important for maintaining stability and safety in robotic systems.

`Recursive Newton-Euler Algorithm (RNEA)`

*`Aim`: RNEA is a dynamic simulation and control algorithm used to calculate the joint torques required for a robotic arm to achieve a desired trajectory or configuration.
*`How it works`: RNEA recursively computes the joint torques by propagating forces and accelerations through the robot's links. It takes into account the inertial properties of the links, such as mass and moment of inertia, to calculate the dynamic response of the robot. This allows for precise control of the arm's motion.

`PD Control (Proportional-Derivative Control)`

*`Aim`: PD control is a common feedback control technique used in robotics to achieve and maintain desired positions or trajectories.
*`How it works`: PD control uses two terms - proportional (P) and derivative (D). The proportional term generates a control signal proportional to the error between the desired and actual position. The derivative term acts to dampen oscillations and reduce overshoot. This combination of terms helps the robotic arm approach and maintain the desired position.

`Computed Torque Control`

*`Aim`: Computed Torque Control, also known as inverse dynamics control, is used to control the motion of a robotic arm precisely by accounting for both the desired trajectory and the dynamics of the robot.
*`How it works`: It involves calculating the torques required to follow a desired trajectory while considering the robot's dynamic model. This control method compensates for inertial and Coriolis forces, allowing for precise control of the robotic arm's motion. It often combines the PD control with the calculated torques to achieve high-performance control.


