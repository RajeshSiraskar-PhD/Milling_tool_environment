# Milling Tool Environment

- Author: Rajesh Siraskar
- Date: 15-March-2025

Reinforcement Learning (RL) for Predictive maintenance (PdM) requires an environment. This environment was developed as part of research conducted and published in the following article:

This environment is based on the OpenGym standards and therefore extensible

Title:  An Empirical Study of the Naïve Reinforce Algorithm for Predictive Maintenance
DOI:    10.1007/s42452-025-06613-1
Link:   https://link.springer.com/article/10.1007/s42452-025-06613-1

About the environment:
- Handles multiple dataset. PHM and NUAA
- Default Rewards: R1: +1.0, R2: -4.0, R3: -0.5

Environment observation state vector:
- axial_force
- force_x, force_y, force_z
- vibration_x, vibration_y, vibration_z
