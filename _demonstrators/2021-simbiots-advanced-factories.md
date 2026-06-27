---
title: "SIMBIOTS Project Demonstrator at Advanced Factories 2021"
collection: demonstrators
category: industrial
venue: "Advanced Factories"
location: "Barcelona, Spain"
date: 2021-06-15
---

![SIMBIOTS Project Demonstrator](/images/simbiots.png)

### Overview

Official demonstrator of the SIMBIOTS project focused on enabling safe human–robot collaboration for Industry 4.0 scenarios, where robots and humans operate in shared workspaces without physical barriers. The project targets improvements in safety, ergonomics, and productivity in industrial environments through deployable collaborative robotic systems.

---

### System Description

The demonstrator was built around a TIAGo robot performing industrial cleaning tasks on real components in a shared workspace with a human operator, requiring continuous physical interaction and adaptation during execution.

The system combined a ROS-based control architecture with real-time task execution, motion control, and force-aware interaction:

- High-level task sequencing coordinating the cleaning process  
- ROS control framework managing motion execution and controller interfaces  
- Integration of force sensing for physical interaction  
- Admittance control converting external forces into motion commands for compliant behaviour  

The admittance control layer enabled the robot to maintain controlled contact with surfaces while dynamically adapting its trajectory in response to human input or disturbances. This was implemented using force sensing at the end-effector and integrated with whole-body control to prioritise stability, collision avoidance, and task execution. The system also incorporated perception and coordination components (e.g., RGB-D sensing and behaviour-based task execution) to detect objects and structure the cleaning task, enabling continuous operation in a shared environment. :contentReference[oaicite:1]{index=1}  

Further technical details and implementation context are available here:  
[SIMBIOTS Project — Human–Robot Cooperation](https://pal-robotics.com/blog/simbiots-project-for-robot-human-cooperation/)

---

### Demonstration

The system was presented at Advanced Factories 2021 in Barcelona, an industrial exhibition focused on automation, robotics, and smart manufacturing, where it was demonstrated live as a collaborative human–robot cleaning task in a public industrial setting.

---

### Media

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/w3N2M6WVnsg"
  title="SIMBIOTS Project Demonstrator — Advanced Factories 2021"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>