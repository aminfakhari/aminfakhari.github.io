---
title: "Research"
permalink: /research/
author_profile: true
---


## Motion and Force Planning for Manipulating Objects by Pivoting
Manipulation of objects by exploiting their contact with the environment can enhance both the dexterity and payload capability of robotic manipulators. A common way to manipulate heavy objects beyond the payload capability of a robot is to use a sequence of pivoting motions, wherein, an object is moved while some contact points between the object and a support surface are kept fixed. In this research, we developed an algorithmic approach for automated plan generation for object manipulation with a sequence of pivoting motions. A plan for manipulating a heavy object consists of a sequence of joint angles of the manipulator, the corresponding object poses, as well as the joint torques required to move the object. The constraint of maintaining object contact with the ground during manipulation results in nonlinear constraints in the configuration space of the robot, which is challenging for motion planning algorithms. Exploiting the fact that pivoting motion corresponds to movements in a subgroup of the group of rigid body motions, SE(3), we presented a novel task-space based planning approach for computing a motion plan for both the manipulator and the object while satisfying contact constraints.

![](https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/ObjectGaiting.gif)