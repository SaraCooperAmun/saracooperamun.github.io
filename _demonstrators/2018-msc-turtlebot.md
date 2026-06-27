---
title: "MSc Robotics Project: TurtleBot SLAM and Object Detection"
collection: demonstrators
category: academic
venue: "Heriot-Watt University"
location: "Edinburgh, UK"
date: 2018-12-01
---

![TurtleBot SLAM](/images/turtlebot_slam.png){: width="300px" }

### Overview

First group robotics project during the MSc in Robotics at Heriot-Watt University (2018–2019), focused on developing a rescue-oriented autonomous navigation system using a TurtleBot platform.

The system combined SLAM-based mapping, autonomous navigation, and object detection to enable the robot to explore an environment, build a map, and identify relevant objects during navigation.

Experiments were conducted in Gazebo simulation and validated on a physical TurtleBot platform, focusing on the integration of perception and navigation for search-and-rescue scenarios.

The project was developed collaboratively by AUDRY Hanako, Sara Cooper, and OLADIPUPO Gideon.

---

### System Description

The system integrated multiple core robotics components into a unified pipeline:

- SLAM for environment mapping  
- AMCL-based localization for pose estimation  
- move_base for autonomous navigation  
- find_object_2d for visual object detection  
- Mapping of detected objects into the global representation  

The combination of these modules enabled the robot to navigate autonomously while detecting and localizing objects in both simulation and real-world experiments.

---

### Contributions

- Integration of SLAM, AMCL, and move_base for autonomous navigation  
- Implementation of object detection using find_object_2d  
- Mapping detected objects into the global environment representation  
- Testing and validation in both simulation (Gazebo) and real TurtleBot hardware  
- Support in system integration and debugging across the group  

---

### Demonstration

#### Simulation

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/lfxeDlCYsO0"
  title="TurtleBot SLAM & Object Detection — Simulation"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>

#### Real Robot

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/UoQJvCftzLU"
  title="TurtleBot SLAM & Object Detection — Real Robot"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>

---

### Resources

- Repository: https://github.com/SaraCooperAmun/Turtlebot_Rescue_Mission  

---

### Technical Highlights

- SLAM-based mapping for environment representation  
- AMCL + move_base for autonomous navigation  
- Visual object detection using find_object_2d  
- Integration of perception and navigation for rescue-style tasks  
- Validation in simulation and real robot experiments  