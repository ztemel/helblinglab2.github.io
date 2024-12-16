---
layout: page
title: Research
---



### Locomotion Strategies
<img align="left" width="220" height="157" style="margin:20px 20px" src="/assets/img/research/gammabot_skating.png" alt="">

<p style="text-align: justify;"> </p>

Bio-inspired, insect-like robots (length < 5cm, mass < 1g) have been in development for more than three decades, and we now have reliable designs for cm-scale mechanisms, repeatable manufacturing processes, and high power-density actuation strategies to enable new vehicles with ever increasing capabilities. However, existing insect-scale robots do not yet have the power, control or mobility necessary to match biological performance. My group is creating a number of robotic platforms that can fly, swim, jump, and crawl, and skate across the water surface to analyze performance across a number of terrains. We employ mathematical modeling to characterize locomotion performance, design new mechanisms and actuators to realize novel robot capabilities,



### Perception and Estimation Systems
<img align="left" width="220" height="159" style="margin:20px 20px" src="/assets/img/research/IMU_bee.jpg" alt="">

<p style="text-align: justify;"> </p>
In an autonomous deployment, robots will need perceive their own state (proprioception) and the surrounding environment (exteroception) to make minor adjustments to their leg or wing trajectories or perform higher-level switching between task-specific behaviors. My group is currently classifying a number of mm-scale sensors based on their accuracy, resolution, and bandwidth, as well as their size, weight, and power consumption to develop a database of suitable sensing, processing, and power systems. We have integrated mm-scale COTS IMUs to estimate absolute orientation and angular velocity, ToF sensors to estimate vehicle height, and high-resolution vision systems to estimate roll velocity on the RoboBee platform. Vision is an important component of robotic perception systems, but computer vision algorithms can be computationally expensive and ill-suited to resource-constrained robotic systems. A current research focus is the integration of mm-scale, high-resolution cameras with simplified computer vision algorithms to run feature detection and pose estimation in a real-time system mm-scale system. We developed an absolute pose estimation system that consisted of a COTS vision sensor (AMS, NANEYE 2C) and a COTS microcontroller (STM32G). Simplifying the environment using LED landmarks and reducing hardware and software complexity, we were able to show real-time operation at 16.5FPS and accuracy within 15mm.



### Power Electronics
<img align="left" width="220" height="292" style="margin:20px 20px" src="/assets/img/research/Nature_cover.png" alt="">

<p style="text-align: justify;"> </p>
Piezoelectric bimorph actuators are the motors of choice for cm-scale robotics platforms due to their high bandwidth and high power densities. To obtain the necessary displacements, these actuators are driven with high fields. Specifically, we send time-varying signals at a frequency of approximately 170Hz and a unipolar amplitude of 200V. We design low mass, high efficiency electronics to step-up the voltage and generate high-voltage, time-varying signals from low-voltage energy sources (e.g., solar cells or batteries). Combining these custom drive electronics and solar cells, we demonstrated the first untethered flight of an insect-scale flapping-wing robot, published in Nature. We continue to develop new designs to perform energy-saving techniques to enable longer mission times.



