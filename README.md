# Rise of the Robot


- [Rise of the Robot](#rise-of-the-robot)
  - [Group F](#group-f)
  - [Overview](#overview)
  - [Features](#features)
  - [Sim Parameters](#sim-parameters)
  - [Requirements](#requirements)
    - [Basics](#basics)
    - [Advanced](#advanced)
    - [Nice to have](#nice-to-have)
  
## Group F
**Contributors**:
- Erich Reichl, ic19b071, local planning
- Matthias Wimmer, mr24b007, global planning

## Overview
**Rise of the Robot** is a robotics simulation project designed to implement a global planning and local execution of a maze navigating robot

## Features
- **Simulation Environment**: A basic ROS environment is provided by <TODO shall we link the package> modified by the contributors (--> Sim Parameters)
- **Global Planning**: a (probably) known Maze is analyzed and waypoints are set using the algorithm (--> Algorithm*s) cost effectiveness is optimized
- **Local Planning**: According to a list of waypoints possible trajectories is simulated and a viable option choosen for execution
- **Kinematic execution**: Based on the Planning the robots actuators are adressed using the ROS publishing scheme
- **Visualization**: Tools for visualizing robot movements and sensor data in RViz.

## Sim Parameters
- tbd

## Requirements
### Basics
- [x] B 1: Set up the ROS environment with the package provided
- [x] B 2: choose the appointment of duties
  - [x] B 2.1: global planning
  - [x] B 2.2: local planning 
- [ ] B 3: get to know your specific topics
- [ ] B 4: Implementation

### Advanced

### Nice to have 