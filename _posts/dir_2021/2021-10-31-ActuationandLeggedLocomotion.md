---
layout: post
title:  "Actuation and Legged Locomotion in Robots"
author: Shaily
categories: [Robotics]
image: assets/images/locomotion_images/loco1024.png
wide_image: assets/images/locomotion_images/loco1024.jpg
thumb_image: assets/images/locomotion_images/loco500.jpg
last_added: true
hidden: false
---
In this advancing era of robotics technology, it comes to us as no surprise that soon such captivating automatons will take on becoming an indispensable part of our lives in facilitating rudimentary tasks amidst making things easier in the mere future.

Delving further into the dynamics of humanoids, this article elaborates upon the indistinctive ways through which a robot’s locomotion can be controlled and monitored to actuate just as human/mammal leg respondents. 

<div align="center">
 <img src="/assets/images/locomotion_images/illustration.png"/>
</div>
<br>

### Why highlight legged locomotion?
For a humanoid to replicate an accurate responsive locomotive system, it intensifies the need for a low-risk, terrain adaptive, and alert stimuli driven system for immaculate results leading to mitigated advancements in automation.
<br>
Hence, just like four-legged animals or two-legged humans, the control and reach about different terrains, or accessibility within secluded places can be made feasible. Not only would it serve as a vital means of locomotion, but also as an omnidirectional platform that can negotiate obstacles with a comparable size of the robot. Explicit mobility capabilities as such proclaim them most efficient for exploration tasks, search and rescue, inspection, and so forth which generally require machines capable of traversing challenging terrain and negotiating obstacles.
<br>



### Overview
A walking robot generates its motion by producing reaction forces between its legs and the terrain on which it is locomoting. Due to this platform’s hybrid nature, several challenges specific to legged locomotion arise when implementing the set of skills necessary to navigate in a real-world environment. A successful motion control structure’s essential feature is the capability to quickly recompute its solution.
<br>
The motion of a walking robot is carried out with the help of reaction forces which are produced by the terrain of locomotion. For an efficient control structure, the robot should be able to recompute the solution of its overlaying obstacles at the earliest. The terrain could be challenging leading to the implementation of crucial skills and features for the bot to navigate in a realistic environment. 

### Actuation and Its Methods
The basic action of causing a machine or a robot to move or operate is referred to as actuation. For the dynamics of locomotion in legged robots, we need to explore the various ways in which actuation can be carried out.

1. **Hydraulic Actuation**

This method has some extremely lucid benefits. These actuators make use of hydraulic oil which provides efficient force density, high power, and extra robustness to impacts. However, the stumbling block in the development of hydraulic actuation is the energetic inefficiency due to the fluid viscous loss and leakage of the servo valve. 

Here is an example of a Hy-Mo hydraulic system wherein, with the servo valve, the leakage is only 10% then it is otherwise.
<div align="center">
 <img src="/assets/images/locomotion_images/hydraulic.png"/>
</div>

2. **Quasi Direct Drive(QDD) Actuation**

To maintain torque control across high bandwidth, the reduction ratio shall be lowered. Such actuators with considerably low reduction ratios are called quasi-direct drive (QDD) actuators. This single-stage increases torque output at the expense of control bandwidth but maintains the ability to back drive the motor for dynamic locomotion. A QDD actuator also ensures transparency in terms of inertia wherein the reflected inertia is much feeble in comparison to the output inertia. Although QDD actuator is used in MIT Cheetah robots which are small legged, for large-scale legged robots, low gear reduction ratio is insufficient to meet its needs.
<div align="center">
 <img src="/assets/images/locomotion_images/cheetah.png"/>
</div>
<h6 style="text-align: center;">MIT Cheetah</h6>

3. **Serial Elastic Actuation(SEA)**

This actuation is most virtuous in compensating for the low torque output of the QDD system. Application of series elasticity to these systems ensures force-controllable actuation with low friction, low impedance, and good bandwidth helping us achieve high-quality force control. The output torque can be controlled by spring deflection while the elastic element stores energy and increases peak power. The fundamentals of this application are derived from Hooke’s law.

<div align="center">
 <img src="/assets/images/locomotion_images/sea.png"/>
</div>
<br>

### Sensory Perception
Both proprioceptive(IMU, encoders, torque sensors) and exteroceptive sensors(RGB-D, CCD, CMOS sensors) are used to measure environmental information. Although RGB-D sensors provide depth estimation, its perception is limited to less than 5m.
<br>

Since force perception is very important to the dynamic control of legged robots, the torque sensor is often mounted on the body or at the end of the leg.
<br>
Visual perception along with IMU sensing vouches for the stable operation of a legged robot. The BigDog robot by Boston Dynamics includes various sensors including the IMU sensor.
<div align="center">
 <img src="/assets/images/locomotion_images/bigdog.png"/>
</div>
<h6 style="text-align: center;">BigDog</h6>
<br>


### Motion Planning
The locomotion performance of a robot largely depends upon navigation mapping and its motion planning. 3D points are heavily robust in memory and hence are narrowed down to grid maps like ITMs(Irregular Triangular Meshes) or DEM’s(Digital Elevation Maps) to comprehend easier environmental frameworks. 
<br>
The map for the legged robot’s locomotion better contain explicit geometric aspects of the partial terrain. Compared to wheeled or tracked robots, legged robots are better at traversing obstacles compared to wheeled or tracked robots since they have more options such as stepping on or over and simply bypassing obstacles. 
<br>
Model Predictive motion planning is another method used to reduce computational burden wherein specialized optimal control solvers leverage the numerical structure of the optimization problem. This is applied by RSL in their robot ANYmal.
<div align="center">
 <img src="/assets/images/locomotion_images/anymal.png"/>
</div>
<h6 style="text-align: center;">Model predictive motion planning in ANYmal</h6>
<br>

### Conclusion
As it has already been stated earlier, legged robots are much more efficient in terms of operation on challenging terrain when compared to conventional field tracked or wheeled robots. Although perception modeling and adaptability enhancement still need to be revved up, multi legged robots have been dynamic and consistent in their performance over the recent years and seem to assure us with much more horizons of astounding development.




### References
- [https://link.springer.com/article/10.1186/s10033-020-00485-9](https://link.springer.com/article/10.1186/s10033-020-00485-9)
- [https://rsl.ethz.ch/research/researchtopics/legged-locomotion.html](https://rsl.ethz.ch/research/researchtopics/legged-locomotion.html)
- [https://www.bostondynamics.com/legacy](https://www.bostondynamics.com/legacy)
- [https://news.mit.edu/2019/mit-mini-cheetah-first-four-legged-robot-to-backflip-0304](https://news.mit.edu/2019/mit-mini-cheetah-first-four-legged-robot-to-backflip-0304)
- [https://www.spiedigitallibrary.org/conference-proceedings-of-spie/5422/0000/Series-Elastic-Actuators-for-legged-robots/10.1117/12.548000.short?SSO=1](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/5422/0000/Series-Elastic-Actuators-for-legged-robots/10.1117/12.548000.short?SSO=1)

