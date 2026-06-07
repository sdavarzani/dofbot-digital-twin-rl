# dofbot-digital-twin-rl
DOFBOT Robotic Arm: Digital Twin &amp; Deep Reinforcement Learning (DRL)

This project focuses on building a high-fidelity "Digital Twin" of the Yahboom DOFBOT 6-DOF robotic arm using ROS 2, Gazebo, and RViz. The ultimate goal is to train a DRL agent to perform precise contact manipulation tasks, such as reaching and button pressing, and evaluating sim-to-real transfer.

Project Goals:

- Build an accurate, dynamic virtual environment modeling the DOFBOT arm, target tables, and operational objects.

- Implement a Gymnasium-style environment wrapper for continuous joint control.

- Apply Deep Reinforcement Learning to optimize precise end-effector reaching and button-pressing objectives.
