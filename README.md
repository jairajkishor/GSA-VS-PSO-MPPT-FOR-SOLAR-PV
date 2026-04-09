# GSA vs PSO MPPT for Solar PV (MATLAB)

## Overview
This project implements and compares Gravitational Search Algorithm (GSA) and Particle Swarm Optimization (PSO) based Maximum Power Point Tracking (MPPT) techniques for solar photovoltaic (PV) systems under partial shading conditions.

The objective is to improve power extraction efficiency by accurately tracking the global maximum power point (GMPP) in scenarios where multiple local maxima exist.

---

## Problem Statement
Conventional MPPT methods such as Perturb and Observe (P&O) are ineffective under partial shading conditions due to the presence of multiple peaks in the power-voltage curve. This leads to reduced efficiency and suboptimal power extraction.

This project addresses:
- Global maximum power point tracking
- Faster convergence
- Improved system efficiency under dynamic conditions

---

## Algorithms Implemented

### Particle Swarm Optimization (PSO)
- Population-based optimization algorithm
- Fast convergence speed
- Suitable for real-time MPPT applications

### Gravitational Search Algorithm (GSA)
- Based on Newtonian gravitational principles
- Strong global search capability
- Effective in avoiding local maxima

---

## System Model
- Solar PV array modeled in MATLAB/Simulink
- DC-DC converter integrated with MPPT controller
- Simulation conditions include:
  - Partial shading
  - Variable solar irradiance
  - Changing load conditions

---

## Results and Observations

| Parameter           | PSO      | GSA      |
|--------------------|----------|----------|
| Convergence Speed  | Fast     | Moderate |
| Accuracy           | High     | Very High|
| Stability          | Good     | Excellent|
| Energy Yield       | Improved | Highest  |

Key observations:
- Both PSO and GSA outperform conventional MPPT methods
- PSO provides faster convergence
- GSA achieves better global optimization under complex conditions
- Overall system efficiency is significantly improved

---

## Simulation Outputs
Include relevant MATLAB/Simulink output plots such as:
- Power vs Time
- Voltage vs Time
- Convergence comparison

---

## Tech Stack
- MATLAB
- Simulink

---

## How to Run
1. Open MATLAB
2. Load the Simulink model file (.slx)
3. Run the simulation
4. Observe outputs using scope blocks

---

## Future Work
- Hybrid PSO-GSA MPPT implementation
- Hardware-based validation
- Integration with real-time monitoring systems
- Comparison with other AI-based MPPT methods

---

## Applications
- Solar energy systems
- Renewable energy optimization
- Smart grid applications
- Power electronics research

---

## Author
Your Name
