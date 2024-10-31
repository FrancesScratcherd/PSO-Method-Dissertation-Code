# PSO-Method-Dissertation-Code

In this repository, I am sharing some of the code from my dissertation on the PSO (Particle Swarm Optimization) method.

My dissertation is largely based on the work of Proffesor Lorenzo Pareschi and Dr Sara Grassi. During the summer of 2024, I undertook a project titled **Mean-Field Techniques in Particle Swarm Optimization** for my master's dissertation at Heriot-Watt University. In this project, I aimed to derive Vlasov-Fokker-Planck type equations that characterize the dynamics of CBO  models—simpler but similar to PSO. Alongside this, I performed numerical testing, which included histogram plots of the SD-PSO (Stochastic Dynamics Particle Swarm Optimization) systems, as well as histogram and PDF comparisons of the analogous Vlasov-Fokker-Planck type equations characterizing the SD-SPO and SD-PSO equations themselves.

## Project Overview

This repository contains code related to the numerical testing and simulations described in Chapter 6 of the dissertation. The focus is on various configurations of the PSO system, specifically examining the effects of memory and local best dynamics.

### Code Files

- **Case 1 - Histogram.ipynb**: Code for the SD-PSO system with memory, focused on minimizing the Ackley function.
- **Case 2 - Histogram.ipynb**: Code demonstrating the dynamics of the SD-PSO system with local best dynamics.
- **Case 3 - Histogram.ipynb**: Further exploration of the SD-PSO system with local and global best dynamics.
- **0.1 - The Original PSO Method.ipynb**: Basic PSO method implementation featuring an animation that visualizes particle swarm convergence.
- **Mean-Field_Techniques_in_PSO.pdf**: The full dissertation document detailing the research and findings.

## Abstract

Particle Swarm Optimization (PSO) is an optimization algorithm famously inspired by bird flocks and fish schools. Recent developments in simpler CBO models have shown that, with appropriate regularization and mean-field techniques, Vlasov-Fokker-Planck type equations can be derived to model the dynamics of the CBO model. This dissertation aims to reproduce recent applications of these techniques to PSO methods to obtain deterministic PDEs analogous to the behavior of the particle system. We then consider how analogous CBO equations can be derived in the small inertia limit, and finally, we discuss discretization techniques and perform a numerical simulation to compare the SD-PSO particle model to the MF-PSO PDE.
