# Solar-PV-cell
#  Perovskite Solar Cell Simulation using COMSOL Multiphysics

This project reproduces and extends the numerical simulations presented in the paper:

**"Comprehensive study of anomalous hysteresis behavior in perovskite-based solar cells"**  
*Mehran Minbashi & Elnaz Yazdani, Scientific Reports, 2022*  
 [DOI: 10.1038/s41598-022-19194-5](https://www.nature.com/articles/s41598-022-19194-5)

##  Project Description

This repository contains COMSOL Multiphysics models that simulate 1D and 2D architectures of perovskite solar cells (PSCs), focusing on the hysteresis behavior in their current-voltage (J–V) characteristics. The simulations implement a drift–diffusion framework coupled with ion migration effects, as detailed in the above-mentioned study.

## Objectives

- Reproduce the J–V hysteresis curves reported in the reference paper using COMSOL.
- Analyze normal vs. inverted hysteresis through parameter variation.
- Investigate the influence of ion migration, scan rate, pre-bias voltage, and interfacial charge dynamics on cell performance.
- Validate the computational results against experimental and simulated data from the literature.

##  Model Overview

###  1D Model
- **Modules Used**: Semiconductor Module
- **Layers**: Electron Transport Layer (ETL), Perovskite Absorber, Hole Transport Layer (HTL)
- **Key Physics**: Drift–diffusion transport equations, recombination, ion migration fluxes

###  2D Model
- **Purpose**: Visualize spatial effects and charge accumulation across interfaces
- **Additions**: 2D geometry, mesh refinement, interface-specific conditions

##  Key Results

- Successfully replicated both *normal* and *inverted* J–V hysteresis loops.
- Demonstrated the effect of ion migration (flux parameters \( g_{ae} \), \( g_{ch} \)) on hysteresis amplitude and shape.
- Showed that pre-bias voltage and scan rate significantly modulate device performance.
- Simulation results were consistent with those reported in the original study.
