---
title: "Research"
permalink: /research/
author_profile: true
---

## Development of a Novel Impedance-Controlled Quasi-Direct-Drive Robot Hand

Most robotic hands and grippers rely on actuators with large gearboxes and force sensors for controlling gripping force. However, this might not be ideal for tasks which require the robot to interact with an unstructured and/or unknown environment. We propose a novel quasi-direct-drive two-fingered robotic hand with variable impedance control in the joint space and Cartesian space. Variable impedance control allows the hand to perform dexterous manipulation tasks while being safe during human-robot interaction. The quasi-direct-drive actuators enable the fingers to handle contact with the environment without the need for complicated tactile or force sensors. The hand demonstrates grasping with force-closure and form-closure, stable grasps in response to disturbances, tasks exploiting contact with the environment, simple in-hand manipulation, and a light touch for handling fragile objects.

**MS Student: [Jay Best](https://www.linkedin.com/in/jay--best/)**

## Motion and Force Planning for Manipulating Objects by Pivoting
Manipulation of objects by exploiting their contact with the environment can enhance both the dexterity and payload capability of robotic manipulators. A common way to manipulate heavy objects beyond the payload capability of a robot is to use a sequence of pivoting motions, wherein, an object is moved while some contact points between the object and a support surface are kept fixed. In this research, we developed an algorithmic approach for automated plan generation for object manipulation with a sequence of pivoting motions. A plan for manipulating a heavy object consists of a sequence of joint angles of the manipulator, the corresponding object poses, as well as the joint torques required to move the object. The constraint of maintaining object contact with the ground during manipulation results in nonlinear constraints in the configuration space of the robot, which is challenging for motion planning algorithms. Exploiting the fact that pivoting motion corresponds to movements in a subgroup of the group of rigid body motions, SE(3), we presented a novel task-space based planning approach for computing a motion plan for both the manipulator and the object while satisfying contact constraints.

**Collaborators: [Dr. Nilanjan Chakraborty](https://me.stonybrook.edu/people/faculty/Chakraborty_Nilanjan.php), [Aditya Patankar](https://www.linkedin.com/in/adityapatankar/)**

<video src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/ObjectGaiting.mp4" controls="controls" style="max-width: 730px;">
</video>

<!---
![](https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/ObjectGaiting.gif)
--->

- A. Fakhari, A. Patankar and N. Chakraborty, "[Motion and Force Planning for Manipulating Heavy Objects by Pivoting](https://ieeexplore.ieee.org/document/9636103)," *2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*, 2021, pp. 9393-9400, doi: 10.1109/IROS51168.2021.9636103.
- A. Patankar, A. Fakhari and N. Chakraborty, "[Hand-Object Contact Force Synthesis for Manipulating Objects by Exploiting Environment](https://ieeexplore.ieee.org/document/9341316)," *2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*, 2020, pp. 9182-9189, doi: 10.1109/IROS45743.2020.9341316.