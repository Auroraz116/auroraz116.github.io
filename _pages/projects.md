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
## DARPA Triage Challenge 
*2024.7 - 2025.5*

<center>
  <img src="https://github.com/Auroraz116/auroraz116.github.io/blob/master/images/darpa.png?raw=true" alt="DARPA" width="50%" height="50%">
  
  <img src="https://github.com/Auroraz116/auroraz116.github.io/blob/master/images/system_software_diagram.png?raw=true" alt="Heart Rate detection Example" width="50%" height="50%">
</center>

- &nbsp; Implemented Python framework for Virtual Heart Rate (pyVHR) for remote photoplethysmography (rPPG), achieving accurate heart rate estimation by introducing HSV color space for precise skin area extraction
- &nbsp; Deployed deep learning model MTTS-CAN for rPPG, improving estimation accuracy by 38% and reducing processing time by 50%
- &nbsp; Containerized ROS nodes for heart rate detection and person segmentation based on YOLOV7 using Docker, improving reproducibility and deployment efficiency
- &nbsp; Implemented YOLOv7 person pose detection on aerial/ground IR imagery to enable visual servoing systems
- &nbsp; Achieved high-performance localization via factor graphs, fusing GPS, LiDAR odometry and IMU for efficient and accurate state estimates

## Proximal Policy Optimization (Walker Training)
*2025.4 - 2025.5*
<center>
<iframe src="https://giphy.com/embed/n3yQNtZai7KGz2Fp7E" width="480" height="317" style="" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/n3yQNtZai7KGz2Fp7E">via GIPHY</a></p>
</center>
- &nbsp; Implemented PPO policy on Deepmind’s Control Suite.

## DiT Flow-Matching Policy for Bimanual Manipulation
*2025.3 - 2025.5*
<center>
  <img src="https://github.com/Auroraz116/auroraz116.github.io/blob/master/images/pouring.png?raw=true" alt="Pouring beans demo" width="50%" height="50%">

  <img src="https://github.com/Auroraz116/auroraz116.github.io/blob/master/images/vit_dit.png?raw=true" alt="VIT_DIT" width="50%" height="50%">
</center>


- &nbsp; 	Implemented flow-matching generative modeling as an alternative to DDPM/DDIM used by the original paper, significantly speeding up inference while achieving optimal accuracy
- &nbsp; 	Implement a transformer-based diffusion policy backbone, consisting of a pretrained ViT as the vision encoderand a DiT as the denoising network, achieving 60% success rate in generalization on bimanual tasks
- &nbsp; 	Collected 1000 demos of a bimanual pouring-bean task we designed (4 hours length) on a tabletop Bi-XArm setup using VR teleoperation

## Digital Twin Development and Integration in Driving Simulation
*2024.1 - 2024.7*
<center>
  <img src="https://github.com/Auroraz116/auroraz116.github.io/blob/master/images/drivesim.png?raw=true" width="60%" height="60%">
</center>

- &nbsp; Extracted high-precision 3D map data from google map and built digital scenes of high accuracy in Roadrunner and Cesium
- &nbsp; Created multiple simulations of real traffic scenarios in Unity and Carla to help redesign the Roosevelt Blvd in Philadelphia, improving safety and accommodating high-capacity transit infrastructure
- &nbsp; Work with Jitsik LLC, a startup company in Mixed Reality, testing the Unity and Unreal API of the Earth to create Virtual Reality models, extending the work for application and completed the pipeline for digital twin development
- &nbsp; Published as the first author: "Pipeline for fast Digital Twin development and integration in Driving Simulation" for the 2024 Road Safety & Simulation Conference

## Quadrotor Control and Motion Planning Algorithm Development
*2024.1 - 2024.4*

<center>
<iframe src="https://giphy.com/embed/XLIHCgxtKtvY2AGlL0" width="270" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/XLIHCgxtKtvY2AGlL0"></a></p>
</center>

- &nbsp; Built a dynamic model of a quadrotor and implemented geometric nonlinear controller with PD control and implemented Dijkstra and A* algorithms to find the shortest path to the goal
- &nbsp; Generated trajectory using mininum snap with inequility constraints and cost optimization, achieving collision-free and high speed (4.1m/s) quadrotor control
- &nbsp; Implemented Kalman filter to predict and update the status of the quadrotor in sensor constrained situations and completed collision-free quadrotor control

## Implementation Control and Path Planning algorithms for Robotic Arm Manipulation
*2024.3 - 2024.5*

<center>
  <iframe src="https://giphy.com/embed/N6OfVk7AznpKHMZTHP" width="404" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/N6OfVk7AznpKHMZTHP"></a></p>
</center>

- &nbsp; Implemented the forward kinematics, Jacobians and velocity kinematics, Inverse kinematics with secondary tasks on Franka Emika PANDA robot arm with 7-DOF for robot manipulation using ROS and Gazebo.
- &nbsp; Developed potential fields controller and a Rapidly-Exploring Random Tree(RRT) planner for the robotic arm for better control and path planning.
- &nbsp; Deployed a full control pipeline for the final competition of stacking blocks and won the first place.

## Query Image Guided Instance Detection and Segmentation Algorithm Development
*2023.10 - 2023.12*

<center>
  <img src="https://github.com/Auroraz116/auroraz116.github.io/blob/master/images/dataset.png?raw=true" alt="Dataset we used to train the model" width="50%" height="50%">
  <img src="https://github.com/Auroraz116/auroraz116.github.io/blob/master/images/result.png?raw=true" alt="How it works" width="50%" height="50%">
</center>

<center>
  <iframe src="https://giphy.com/embed/Q4TI5JxSLEdYnawqsU" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/Q4TI5JxSLEdYnawqsU"></a></p>
</center>

- &nbsp; Developed a query image-guided real-time instance detection and segmentation algorithm based on YOLACT and ResNet50 architecture for common objects such as iPads/phones, cups and T-shirts
- &nbsp; Created a dataset with thousands of sythetic pictures and frames extracted from manually taken videos, ensuring rigorous testing, training and validation of the model
- &nbsp; Trained model based on the dataset and validated the feasibility and generalization of our model, achieving over 0.8 confidence level for class prediction and processing frame eate of 16.12fps on laptop

## Tongji University DIAN Driverless Formula Student Autonomous Team 
*2022.10 - 2023.7*
- &nbsp; Developed a comprehensive perception algorithm based on ROS to detect the exact location and different colors of pile buckets within 20m, improving the efficiency of path planning for car racing
- &nbsp; Created a 3D point cloud map reconstruction of test field and real-time positioning of racing car by utilizing multisensor fusion, improving the accuracy by 5% on advanced SLAM framework
- &nbsp; Participated in Formula Student Autonomous China (2021) and won Third Place overall

## Tongji University DIAN Racing Formula Student Electric Team
*2021.10 - 2023.7*
<center>
  <img src="https://github.com/Auroraz116/auroraz116.github.io/blob/master/images/racing.gif?raw=true" width="50%" height="50%">
</center>

- &nbsp; Designed a wheel side sensor node consisting of an IMU and temperature sensors to measure tire parameters, thus improving chassis tuning efficiency and optimizing VCU dynamic algorithms
- &nbsp; Introduced a resource sharing platform called Yuque to over 100 group members. Created more than 50 technical and administrative documentations regarding embedded development and dynamic control algorithms
- &nbsp; Participated in Formula Student Electric China (FSEC) Design Final Defense as Chief Electrical Engineer, achieving Second Place in Design Final Defense and First Prize (fourth place) in FSEC overall

## Virtual Prototype Technology Based on Adams/Car 
*2022.10 - 2022.12*
- &nbsp; Built a VW car model on Adams/Car, laying foundation for virtual simulation of vehicle dynamic performances
- &nbsp; Conducted a comprehensive multibody dynamics simulation based on Adams/Car and analyzed simulation results from virtual prototype in MATLAB, contributing to cost reduction and experimental efficiency elevation
- &nbsp; Established electrical control systems such as ABS and ESP through joint simulation between Adams/Car and MATLAB/SIMULINK, achieving the combination of virtual prototype and control theory
