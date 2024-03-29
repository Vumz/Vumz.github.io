---
title: "Healthcare Robotics Research"
excerpt: "Robotics research ranging from sensor design to realistic simulation. <br/><img src='/images/ResearchLanding.png'>"
collection: portfolio
---

**Date**: August 2017 – July 2020

**Skill/Platforms used**: Python, Capacitive Sensing, Tensorflow, ROS, Teensy, EC2, Pybullet, Blender, OpenGL, C/C++

**Summary**: 

[Z. Erickson, V. Gangaram, A. Kapusta, C. K. Liu, and C. C. Kemp, “Assistive Gym: A Physics Simulation Framework for Assistive Robotics,” (Submitted) 2020 International Conference on Robotics and Automation (ICRA)](https://ieeexplore.ieee.org/abstract/document/9197411)

*Abstract*

Autonomous robots have the potential to serve as versatile caregivers that improve quality of life for millions of people worldwide. Yet, conducting research in this area presents numerous challenges, including the risks of physical interaction between people and robots. Physics simulations have been used to optimize and train robots for physical assistance, but have typically focused on a single task. In this paper, we present Assistive Gym, an open source physics simulation framework for assistive robots that models multiple tasks. It includes six simulated environments in which a robotic manipulator can attempt to assist a person with activities of daily living (ADLs): itch scratching, drinking, feeding, body manipulation, dressing, and bathing. Assistive Gym models a person's physical capabilities and preferences for assistance, which are used to provide a reward function. We present baseline policies trained using reinforcement learning for four different commercial robots in the six environments. We demonstrate that modeling human motion results in better assistance and we compare the performance of different robots. Overall, we show that Assistive Gym is a promising tool for assistive robotics research.

[Z. Erickson, H. M. Clever, V. Gangaram, G. Turk, C. K. Liu, and C. C. Kemp, “Multidimensional Capacitive Sensing for Robot-Assisted Dressing and Bathing,” 2019 International Conference on Rehabilitation Robotics (ICORR), 2019. (Best Student Paper Award)](https://ieeexplore.ieee.org/abstract/document/8779542)

*Abstract*

Robotic assistance presents an opportunity to benefit the lives of many people with physical disabilities, yet accurately sensing the human body and tracking human motion remain difficult for robots. We present a multidimensional capacitive sensing technique that estimates the local pose of a human limb in real time. A key benefit of this sensing method is that it can sense the limb through opaque materials, including fabrics and wet cloth. Our method uses a multielectrode capacitive sensor mounted to a robot's end effector. A neural network model estimates the position of the closest point on a person's limb and the orientation of the limb's central axis relative to the sensor's frame of reference. These pose estimates enable the robot to move its end effector with respect to the limb using feedback control. We demonstrate that a PR2 robot can use this approach with a custom six electrode capacitive sensor to assist with two activities of daily living—dressing and bathing. The robot pulled the sleeve of a hospital gown onto able-bodied participants' right arms, while tracking human motion. When assisting with bathing, the robot moved a soft wet washcloth to follow the contours of able-bodied participants' limbs, cleaning their surfaces. Overall, we found that multidimensional capacitive sensing presents a promising approach for robots to sense and track the human body during assistive tasks that require physical human-robot interaction.

<figure class="video_container">
  <iframe src="https://www.youtube.com/embed/3qKkkx9wshY" frameborder="0" allowfullscreen="true"> </iframe>
</figure>



