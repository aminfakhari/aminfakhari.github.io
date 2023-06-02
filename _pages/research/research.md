---
title: "Research"
permalink: /research/
author_profile: true
---

## Development of a Novel Impedance-Controlled Quasi-Direct-Drive Robot Hand

Most robotic hands and grippers rely on actuators with large gearboxes and force sensors for controlling gripping force. However, this might not be ideal for tasks which require the robot to interact with an unstructured and/or unknown environment. We proposed a novel quasi-direct-drive (QDD) two-fingered robotic hand with variable impedance control in the joint space and Cartesian space. Variable impedance control allows the hand to perform dexterous manipulation tasks while being safe during human-robot interaction. The quasi-direct-drive actuators enable the fingers to handle contact with unstructured environment without the need for complicated tactile or force sensors. The hand demonstrates grasping with force-closure and form-closure, stable grasps in response to disturbances, tasks exploiting contact with the environment, simple in-hand manipulation, and a light touch for handling fragile objects.

**MS Student: [Jay Best](https://www.linkedin.com/in/jay--best/)**

<table style="height:auto; width:auto;" cellspacing="0" cellpadding="0">
  <tr>
    <td><img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/In-Hand_Manipulation_RubberBall.gif" width=auto height=auto alt=""></td>
    <td><img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/Smack_and_Snatch_Egg.gif" width=auto height=auto alt=""></td>
	<td><img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/Picking_up_a_Coin.gif" width=auto height=auto alt=""></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/Grasp_in_Response_to_Disturbance.gif" width=auto height=auto alt=""></td>
    <td><img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/In-Hand_Manipulation_Pushing.gif" width=auto height=auto alt=""></td>
	<td><img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/Grasping_Egg.gif" width=auto height=auto alt=""></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/Opening_WaterBottle.gif" width=auto height=auto alt=""></td>
    <td><img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/FormClosure.gif" width=auto height=auto alt=""></td>
	<td><img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/Grasping_Card.gif" width=auto height=auto alt=""></td>
  </tr>
</table>

<hr>

## Motion and Force Planning for Manipulating Objects by Pivoting
Manipulation of objects by exploiting their contact with the environment can enhance both the dexterity and payload capability of robotic manipulators. A common way to manipulate heavy objects beyond the payload capability of a robot is to use a sequence of pivoting motions, wherein, an object is moved while some contact points between the object and a support surface are kept fixed. In this research, we developed an algorithmic approach for automated plan generation for object manipulation with a sequence of pivoting motions. A plan for manipulating a heavy object consists of a sequence of joint angles of the manipulator, the corresponding object poses, as well as the joint torques required to move the object. The constraint of maintaining object contact with the ground during manipulation results in nonlinear constraints in the configuration space of the robot, which is challenging for motion planning algorithms. Exploiting the fact that pivoting motion corresponds to movements in a subgroup of the group of rigid body motions, SE(3), we presented a novel task-space based planning approach for computing a motion plan for both the manipulator and the object while satisfying contact constraints.

**Collaborators: [Dr. Nilanjan Chakraborty](https://me.stonybrook.edu/people/faculty/Chakraborty_Nilanjan.php), [Aditya Patankar](https://www.linkedin.com/in/adityapatankar/)**

<table style="height:auto; width:auto;" cellspacing="0" cellpadding="0">
  <tr>
    <td><img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/Manipulation_Pivoting.gif" width=auto height=auto alt=""></td>
    <td><img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/Cuboid.gif" width=auto height=auto alt=""></td>
    <td><img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/Cylinder.gif" width=auto height=auto alt=""></td>
  </tr>
</table>

<table style="height:auto; width:auto;" cellspacing="0" cellpadding="0">
  <tr>
    <td><img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/Panda_Cuboid.gif" width=auto height=auto alt=""></td>
    <td><img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/Panda_Cylinder.gif" width=auto height=auto alt=""></td>
  </tr>
</table>

**Publications:**
- A. Fakhari, A. Patankar and N. Chakraborty, "[Motion and Force Planning for Manipulating Heavy Objects by Pivoting](https://ieeexplore.ieee.org/document/9636103)," *2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*, 2021, pp. 9393-9400, doi: 10.1109/IROS51168.2021.9636103.
- A. Patankar, A. Fakhari and N. Chakraborty, "[Hand-Object Contact Force Synthesis for Manipulating Objects by Exploiting Environment](https://ieeexplore.ieee.org/document/9341316)," *2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*, 2020, pp. 9182-9189, doi: 10.1109/IROS45743.2020.9341316.

<hr>


## Computing a Task-Dependent Grasp Metric Using Second-Order Cone Programs
Evaluating a grasp generated by a set of hand-object contact locations is a key component of many grasp planning algorithms. In this research, we presented a novel second-order cone program (SOCP) based optimization formulation for evaluating a grasps’ ability to apply wrenches to generate a linear motion along a given direction and/or an angular motion about the given direction. Our quality measure can be computed efficiently since the SOCP is a convex optimization problem, which can be solved optimally with interior point methods. A key feature of our approach is that we can consider the effect of contact wrenches from any contact of the object with the environment. This is different from the extant literature where only the effect of finger-object contacts is considered. Exploiting the environmental contact is useful in many manipulation scenarios either to enhance the dexterity of simple hands or improve the payload capability of the manipulator. In contrast to most existing approaches, our approach also takes into account the practical constraint that the maximum contact force that can be applied at a finger-object contact can be different for each contact. We can also include the effect of external forces like gravity, as well as the joint torque constraints of the fingers/manipulators. Furthermore, for a given motion path as a constant screw motion or a sequence of constant screw motions, we can discretize the path and compute a global grasp metric to accomplish the whole task with a chosen set of finger-object contact locations.

**Collaborators: [Dr. Nilanjan Chakraborty](https://me.stonybrook.edu/people/faculty/Chakraborty_Nilanjan.php), [Aditya Patankar](https://www.linkedin.com/in/adityapatankar/)**

**Publication:**
- A. Fakhari, A. Patankar, J. Xie and N. Chakraborty, "[Computing a Task-Dependent Grasp Metric Using Second-Order Cone Programs](https://ieeexplore.ieee.org/document/9636197)," *2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*, 2021, pp. 4009-4016, doi: 10.1109/IROS51168.2021.9636197.

<hr>


## Trajectory Planning of Walking with Different Step Lengths of a Seven-Link Biped Robot: ##
Most of the essential parameters of human walking can be captured with a seven-link planar biped robot. In this project, dynamics modeling and trajectory planning of a seven-link planar biped robot walking on level ground with a ditch or stairs were studied. The hip and foot trajectories were designed in Cartesian space using polynomial interpolation such that to vanish the impact effect of feet with the ground. The key parameters of the hip joint trajectory in the x-axis direction were obtained using boundaries of biped stable region during the walking to satisfy the dynamic stability of the robot. The highest position of the swing foot ankle joint in the x- and z-axis direction was optimized with two different fitness functions. A novel method for trajectory planning of walking with different step lengths, uses for online trajectory planning, was proposed. Moreover, the effectiveness of the proposed method was verified by simulation and experimental results.

<center>
<img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/Biped/Biped_Robot.gif" style="width: 30%; height: 30%;" alt="">
</center>

<p style="text-align:center;"><img src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/Biped/Biped_Robot.gif" style="width: 30%; height: 30%;" alt=""></p>


**Publications:**
- A. Fattah and A. Fakhari, "[Trajectory Planning of Walking with Different Step Lengths of a Seven-Link Biped Robot](https://asmedigitalcollection.asme.org/IDETC-CIE/proceedings-abstract/IDETC-CIE2010/44106/1361/356930)," *ASME International Design Engineering Technical Conferences & Computers and Information in Engineering Conference (IDETC/CIE)*, Montreal, Quebec, Canada, Aug. 2010. 
- A. Fattah, A. Fakhari, and S. Behbahani, "[Dynamics Modeling and Trajectory Planning of a Seven-Link Planar Biped Robot](https://www.researchgate.net/publication/260772830_Dynamics_Modeling_and_Trajectory_Planning_of_a_Seven-Link_Planar_Biped_Robot)," *17th Annual (International) Conference on Mechanical Engineering (ISME)*, Tehran, Iran, May 2009.

<hr>

<!---
bgcolor="#000000" 
bordercolor="#ffffff" 
<video src="https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/ObjectGaiting.mp4" controls="controls" style="max-width: 730px;">
</video>

![](https://raw.githubusercontent.com/aminfakhari/aminfakhari.github.io/master/_pages/research/ObjectGaiting.gif)
--->
