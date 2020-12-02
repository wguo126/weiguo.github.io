---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Robotic Design Studio (RDS)
![](../images/slides.PNG) [Demo Slides]()

Our group design an uneven bar gynmastic robot:
- Complete mechanical and electrical design of a three link robot
  * Top link is "hand", use pancake motor driven by ESC to grab the bar
  * Middle part is "muscles", contains two brushless motors driven by amplifier to rotate between links
  * Bottom part is "brain", contains E-stop, battery, Relay, two Roboteq amplifier.
![](../images/Picture1.png)
- MatLab simulation of Giant Swing and release-catch
  * Use Euler-Lagrange equations to build the frame of a triple pendulum, simulate the swing and collision phase
  * Use energy-shape controller to pump up the robot
  * Use the position and velocity of the centroid to determine the time of releasing
![](../images/gif1.gif)

<br><br><br>

## Pose Tracker
![](../images/hackaday.png) [Hackaday Project](https://hackaday.io/project/172394-pose-tracker)

![](../images/youtube.PNG) [Demo Video](https://www.youtube.com/watch?v=8D80CxtRYak&feature=emb_logo)

Design a rotating camera to track human movement and evaluate posture
- Components: ESP CAM, Mini Pan-Tilt Kit, and FTDI
- Algorithm: PoseNet, tensorflow.js
- Use visual angle to track movements that increase robustness

<br><br><br>

## Glossy Percpetion
![](../images/slides.PNG) [Demo Slides]()

Use statistics to understand glossy perception
- use subband analysis and histogram manipulation (s-curve, λ-curve) to estimate the glossiness of texture
- find the relations of subband histogram with generalized Gaussian function of textures
![](../images/Picture2.png)

<br><br><br>

## GaN-HEMT performance on DC-DC converter
![](../images/slides.PNG) [Demo Slides]()
- Soft-switching time calculation
  * Established a mathematical model by constructing an accurate numerical fitting function that characterizes the relationship between voltage and parasitic capacitance
  * Investigated partial soft-switching with insufficient time and voltage inverse with abundant deadtime
  * construct power loss model with negative voltage turning-off feature of GaN-HEMT
![](../images/Picture3.png)

- Established power loss model with frequency and voltage range
  * optimized inductance and transformer ratio under wide voltage range and frequency
  * compared power loss, soft-switching range of MOSFET and GaN-HEMT
![](../images/Picture4.png)

Publication: Jiabin Liu, Xi Xiao, Hongwei Mei, Soft switching analysis of dual active bridge DC-DC converter based on GaN-HEMT device, in Transactions of China Electrotechnical Society,2019,34(S2):534-542.








