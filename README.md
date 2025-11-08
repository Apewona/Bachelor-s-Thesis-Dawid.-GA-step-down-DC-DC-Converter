# Electrical Faculty – Bialystok University of Technology  
## Bachelor's Thesis  

## Author: 
Dawid Ostaszewicz  
## Supervisor: 
dr inż. Krzysztof Rogowski  
## Title: 
Utilizing Genetic Algorithms for the Optimization of a Voltage Step-Down DC/DC Converter  
## Location and Year: 
Bialystok, 2024  
## Language
Polish

---

## Abstract

This thesis focuses on the analysis of the controller tuning problem in a control system collaborating with a numerical model of voltage step-down converters. The use of genetic algorithms represents a novel approach compared to traditional methods, which rely on mathematical analysis or empirical tuning. Genetic algorithms employ stochastic processes for optimization, providing an alternative method for determining optimal controller parameters with high precision.

The initial chapters describe the formulation of the state-space model of switching converters and the discretization of these equations. These sections concentrate on mathematical modeling of electrical systems, presenting fundamental assumptions and simplifications used in the modeling process.

The main part of the thesis details the operation of genetic algorithms for optimizing the presented problem. The principles of the algorithm are explained, including the biological foundations that inspired it. Each segment of the implemented program is described, followed by verification of the program’s performance alongside the control system model. Optimal controller settings are determined for two different control systems.

Finally, the thesis presents a comparative analysis of control systems using integral performance criteria. The results demonstrate the effectiveness of genetic algorithms in optimizing controller parameters for DC/DC converters.

---

## Table of Contents

1. Introduction  
   1.1 Purpose and Scope  
   1.2 Methodology  
   1.3 Characteristics of the Thesis  
2. Discrete Model of Buck Converter with LC Filter, Resistive Load, and Two-State Control System  
   2.1 Open-Switch Discrete Model  
   2.2 Closed-Switch Discrete Model  
   2.3 Buck Converter Model Operation with LC Filter and Resistive Load  
   2.4 Two-State Control System with PI Controller  
   2.5 Chapter Summary  
3. Step-Down Converter with Two-Quadrant Switch, Integral Criteria, and Controller Tuning  
   3.1 Dynamics, Scheme, and Simulation  
   3.2 Integral Quality Indices  
   3.5 Chapter Summary  
4. Genetic Algorithms in Optimization and Control Theory  
   4.1 General Structure  
   4.2 Defining Genotypes and Phenotypes  
   4.3 Population Structure, Selection, Crossover, and Mutation  
   4.4 Genetic Algorithm Program Structure for Controller Tuning  
   4.5 Chapter Summary  
5. Results of Genetic Algorithm and Controller Parameter Tuning  
   5.1 Example Program Operation  
   5.2 Problem Space Overview  
   5.3 Determination of Suboptimal Minima  
   5.4 Searching on Integration Gain Boundary  
   5.6 Chapter Summary  
6. Analysis of Obtained Control Systems  
   6.1 Signal Analysis from MATLAB Scripts with Optimal Parameters  
   6.2 Comparison of Buck Converter Models in MATLAB and Simulink  
   6.3 Small-Signal Reproduction of Buck Converter  
   6.4 Small-Signal Reproduction with Two-Quadrant Switch  
   6.5 Chapter Summary  
7. Thesis Summary  
Bibliography  
Appendices 1–5  

---

## Quick Start Guide

### Step 1 – Model Setup
- Load the discrete model of the Buck converter in MATLAB.
- Ensure all system parameters are correctly initialized.
- Verify the two-state PI control system implementation.

### Step 2 – Genetic Algorithm Optimization
- Run the genetic algorithm program included in the appendices.
- Define population, crossover, mutation, and selection parameters.
- Execute the optimization to determine controller settings.

### Step 3 – Verification and Analysis
- Simulate the optimized controller with the converter model in MATLAB and Simulink.
- Analyze transient responses and steady-state performance.
- Compare integral performance criteria for multiple system configurations.

---

## Acknowledgements

I would like to express my sincere gratitude to the **Faculty of Electrical Engineering at Bialystok University of Technology** for providing academic and technical support throughout this work. I also extend my thanks to my supervisor, **dr inż. Krzysztof Rogowski**, for guidance, constructive feedback, and for sharing valuable expertise in control systems and power electronics.

---


