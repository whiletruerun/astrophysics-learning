# Orbital Motion Simulation using Python

This project simulates planetary orbital motion using Newton's Law of Gravitation and numerical integration techniques in Python.

## Overview

The goal of this project was to understand how numerical methods can be used to model the motion of a planet orbiting a star.

Using gravitational force calculations and Euler integration, I simulated the changing position and velocity of a planet over time and visualized its orbital trajectory.

Currently, the simulation uses approximate Earth-Sun parameters, but I plan to extend this project using exoplanet data from NASA's Exoplanet Archive.

## Physics Concepts Used

### Newton's Law of Gravitation

The gravitational force between the star and planet determines the planet's acceleration.

:contentReference[oaicite:0]{index=0}

### Vis-Viva Equation

The initial orbital velocity is estimated using the vis-viva equation:

:contentReference[oaicite:1]{index=1}

where:
- \(r\) is the instantaneous orbital distance
- \(a\) is the semi-major axis

### Euler Numerical Integration

The simulation updates velocity and position iteratively over small time steps.

Although Euler integration is simple to implement, numerical error accumulates over time, causing orbital drift.

## Tools Used

- Python
- NumPy
- Matplotlib

## Features

- Simulates elliptical orbital motion
- Calculates gravitational acceleration dynamically
- Uses numerical integration to update velocity and position
- Visualizes orbital trajectories
- Supports adjustable orbital parameters

## What I Learned

- Basics of computational orbital mechanics
- Numerical integration behavior and stability
- Error accumulation in Euler's method
- Implementing physics-based simulations in Python
- Using the vis-viva equation to estimate orbital velocity

## Future Improvements

- Implement 4th-order Runge-Kutta (RK4)
- Implement leapfrog integration
- Compare integration method stability
- Add multi-body simulations
- Use real exoplanet datasets from NASA Exoplanet Archive

## Sample Output

(Add orbit plot image here)

## Note

This is a beginner-level computational physics project created while learning numerical simulation and orbital mechanics concepts.
