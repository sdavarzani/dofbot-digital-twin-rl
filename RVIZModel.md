 ## Milestone 1: Robot Modeling in RViz

The first milestone of the DOFBOT Digital Twin project focuses on creating a simplified robot model for visualization in **RViz**.

In this step:
- A **URDF** model of the DOFBOT is created.
- The original STL files are modified for each robot link.
- The **kinematic chain** is defined using revolute joints.
- The robot model is verified in RViz.
- Joints motion are tested using **joint_state_publisher_gui**.

It should be noted that the original STL files were obtained from an open-source CAD model [link](https://grabcad.com/library/robotics-arm-with-feeding-spoon-1) and then modified 
and reorganized for each joint.
The mesh files were separated into individual robot links, and the joint pivot coordinates were measured and adjusted so the model could be used for simulation in **RViz** and later 
in **Gazebo**.
Since the original STL files were not directly prepared for ROS simulation, additional work was required to define the correct link structure, joint origins, joint axes, and coordinate
alignment in the URDF.


Finally, the model successfully loads in RViz, and all joints can be moved using "joint_state_publisher_gui".

**Simulation Preview**

Here is the simulation in RViz:
<img width="1920" height="1080" alt="photo_5927183541865221809_w" src="https://github.com/user-attachments/assets/733d57a7-2a6a-4ea6-93ab-1d9034b91d84" />
