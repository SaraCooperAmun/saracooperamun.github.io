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
This was my **first group robotics project** during the MSc in Robotics at **Heriot-Watt University (2018–2019)**. The goal was to develop a **rescue mission system** using a TurtleBot:

- Build a **map of the environment** (SLAM)  
- Navigate **autonomously** to multiple goal locations  
- Detect **markers/objects** along the way  
- Integrate object positions into the generated map  

Simulation was performed in **Gazebo**, with testing on a real TurtleBot. The project focused on combining **autonomous navigation** with **object recognition** for potential applications in search-and-rescue.

This project was conducted by **AUDRY Hanako, Sara Cooper, and OLADIPUPO Gideon**.

---

### My Contribution
I contributed to:

- **Integration of SLAM, AMCL localization, and move_base navigation** for autonomous movement  
- Implementation of **object detection using find_object_2d** and mapping of detected markers  
- Testing in both **simulation and real TurtleBot hardware**  
- Coordinating code integration and debugging across the group  

The project repository [Turtlebot Obstacle Avoidance](https://github.com/SaraCooperAmun/Turtlebot_Rescue_Mission). 

---
### Project Videos

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

### Technical Highlights
- Autonomous navigation in pre-built maps using **AMCL + move_base**  
- Integration with **find_object_2d** for marker recognition  
- Real-time mapping and object localization in both **simulation and hardware**  
- Demonstrates **rescue-oriented applications** for autonomous mobile robots  
