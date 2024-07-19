---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

======
## Quadrotor Control and Motion Planning Algorithm Development

<p>
<iframe src="https://giphy.com/embed/XLIHCgxtKtvY2AGlL0" width="270" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/XLIHCgxtKtvY2AGlL0">via GIPHY</a></p>
<iframe src="https://giphy.com/embed/WKhTzrUSHPKSmavS7O" width="270" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/WKhTzrUSHPKSmavS7O">via GIPHY</a></p>
</p>

- &nbsp; Built a dynamic model of a quadrotor and implemented geometric nonlinear controller with PD control and implemented Dijkstra and A* algorithms to find the shortest path to the goal
- &nbsp; Generated trajectory using mininum snap with inequility constraints and cost optimization, achieving collision-free and high speed (4.1m/s) quadrotor control

## Implementation Control and Path Planning algorithms for Robotic Arm Manipulation
![Franka Emika PANDA Robot Arm](https://github.com/Auroraz116/auroraz116.github.io/tree/master/images/1.png,https://github.com/Auroraz116/auroraz116.github.io/tree/master/images/8.png)
- &nbsp; Implement the forward kinematics, Jacobians and velocity kinematics, Inverse kinematics with secondary tasks on Franka Emika PANDA robot arm with 7-DOF for robot manipulation using ROS and Gazebo.
- &nbsp; Developed potential fields controller and a Rapidly-Exploring Random Tree(RRT) planner for the robotic arm for better control and path planning.
- &nbsp; Deployed a full control pipeline for the final competition of stacking blocks and won the first place.


## Query Image Guided Instance Detection and Segmentation Algorithm Development
- &nbsp; Developed a query image-guided real-time instance detection and segmentation algorithm based on YOLACT and ResNet50 architecture for common objects such as iPads/phones, cups and T-shirts
- &nbsp; Created a dataset with thousands of sythetic pictures and frames extracted from manually taken videos, ensuring rigorous testing, training and validation of the model
- &nbsp; Trained model based on the dataset and validated the feasibility and generalization of our model, achieving over 0.8 confidence level for class prediction and processing frame eate of 16.12fps on laptop

## Digital Twin for Driving as Planning Support Tool 
- &nbsp; Work with Jitsik LLC, a startup company in Mixed Reality, testing the Unity and Unreal API of the Earth to create Virtual Reality models, extending the work for application as a planning support tool
- &nbsp; Extracted high-precision 3D map data from google map and built scenes of high accuracy in Roadrunner
- &nbsp; Created complicated simulations of real traffic scenarios to help redesign the Roosevelt Blvd in Philadelphia, improving safety and accommodating high-capacity transit infrastructure

## Virtual Prototype Technology Based on Adams/Car 
- &nbsp; Built a VW car model on Adams/Car, laying foundation for virtual simulation of vehicle dynamic performances
- &nbsp; Conducted a comprehensive multibody dynamics simulation based on Adams/Car and analyzed simulation results from virtual prototype in MATLAB, contributing to cost reduction and experimental efficiency elevation
- &nbsp; Established electrical control systems such as ABS and ESP through joint simulation between Adams/Car and MATLAB/SIMULINK, achieving the combination of virtual prototype and control theory

## Tongji University DIAN Driverless Formula Student Autonomous Team 
- &nbsp; Developed a comprehensive perception algorithm based on ROS to detect the exact location and different colors of pile buckets within 20m, improving the efficiency of path planning for car racing
- &nbsp; Created a 3D point cloud map reconstruction of test field and real-time positioning of racing car by utilizing multisensor fusion, improving the accuracy by 5% on advanced SLAM framework
- &nbsp; Participated in Formula Student Autonomous China (2021) and won Third Place overall

## Tongji University DIAN Racing Formula Student Electric Team
- &nbsp; Designed a wheel side sensor node consisting of an IMU and temperature sensors to measure tire parameters, thus improving chassis tuning efficiency and optimizing VCU dynamic algorithms
- &nbsp; Introduced a resource sharing platform called Yuque to over 100 group members. Created more than 50 technical and administrative documentations regarding embedded development and dynamic control algorithms
- &nbsp; Participated in Formula Student Electric China (FSEC) Design Final Defense as Chief Electrical Engineer, achieving Second Place in Design Final Defense and First Prize (fourth place) in FSEC overall
