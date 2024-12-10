# Multi-Robot Firefighting Simulation

This repository contains the code and simulation setup for our *Multi-Robot Firefighting System, developed as part of the final project for **MAE598* at Arizona State University (ASU). The simulation uses the *Python version of the Robotarium Simulator* and implements a *Potential Field Control Model* to navigate firefighting robots between fire locations while avoiding obstacles and managing energy constraints.

## Project Overview

The project demonstrates the capabilities of a multi-robot system in a simulated firefighting task. It features:
- *Multi-Robot Coordination*: Five autonomous robots working together to locate and extinguish fires.
- *Obstacle Avoidance*: Dynamic path planning and obstacle evasion using potential field control.
- *Battery Management*: Robots autonomously monitor their battery levels and make decisions accordingly:
  - Robots navigate to the nearest charging station when their battery drops below 25%.
  - After recharging, robots resume their firefighting tasks.

## Simulation Environment

The simulation is developed using the *Python version of the Robotarium Simulator*, which provides a robust framework for designing and testing multi-robot systems. The robots use a potential field control approach to navigate the environment and complete tasks efficiently.

### Control Logic
1. Robots are assigned to firefighting tasks based on the nearest fire location.
2. Obstacles are avoided by incorporating repulsive forces into the potential field calculations.
3. Battery levels are monitored continuously to ensure the robots can complete tasks without interruption.
4. Low-battery robots autonomously return to charging stations and rejoin the task queue once recharged.

## Acknowledgments

This project was developed as part of *MAE598* at **Arizona State University**. Special thanks to the creators of the **Robotarium Simulator** for providing an excellent platform for multi-robot simulation and control.
