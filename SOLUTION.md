# UAV Group Flight Simulation Using a Digital Twin and Nonlocal Virtual Potential

## Project overview

This project is based on my coursework on modeling and control of a UAV group using a digital twin and a nonlocal virtual potential.

The goal of the project is to simulate the motion of a group of UAVs inside a bounded flight area. The model is designed so that UAVs remain inside the flight corridor and avoid collisions with each other and with the boundary.

## Method

The UAV group is modeled as a system of moving agents. Each UAV is affected by a nonlocal virtual potential, which creates repulsion from other UAVs and from the boundary of the area.

The equations of motion are solved numerically using the Verlet integration algorithm. The model was implemented in Wolfram Mathematica.

## Results

The project includes simulations of:

- a single UAV moving inside a circular bounded area;
- a group of 13 UAVs moving inside the same area;
- UAV trajectories and velocity components over time;
- collision avoidance behavior caused by the virtual repulsive potential.

The simulations show that the UAVs remain inside the given flight area and avoid direct contact with each other.

## Relevance

Although this project does not use machine learning directly, it is connected with my research interests in mathematical modeling, UAV digital twins, and computer vision for drones.

This project can be extended in the future with ML/DL methods, for example for trajectory prediction, anomaly detection, environment perception, or decision support for UAV group control.

## Full report and source code

The full coursework report in English is attached to this repository as a PDF file.

The Wolfram Mathematica notebook used for the simulations is available here:

[Wolfram Mathematica notebook](https://drive.google.com/file/d/1ILijcdKWJZg_yb8vebz4tSgXyCDc9Rp6/view?usp=drivesdk)
