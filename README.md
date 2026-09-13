# Aircraft Wing Optimization using GA, PSO and TOC

Optimization of an aircraft wing design using three evolutionary and bio-inspired optimization algorithms: Genetic Algorithm (GA), Particle Swarm Optimization (PSO), and Tornado Optimization with Coriolis (TOC).

## Overview

This project investigates the use of population-based optimization techniques for aircraft wing aerodynamic design.

The NASA Common Research Model (CRM) wing is used as the aerodynamic model, with OpenAeroStruct and OpenMDAO used for aerodynamic analysis and optimization.

The objective is to improve the wing design by optimizing aerodynamic performance while comparing the behavior of different optimization algorithms.

## Optimization Methods

- Genetic Algorithm (GA)
- Particle Swarm Optimization (PSO)
- Tornado Optimization with Coriolis (TOC)

## Aerodynamic Model

The project uses:

- NASA Common Research Model (CRM) wing
- OpenAeroStruct
- OpenMDAO
- Aerodynamic analysis based on lift and drag performance

## Project Workflow

1. Define the aircraft wing geometry
2. Set up the aerodynamic analysis
3. Evaluate the baseline wing design
4. Define the optimization objective
5. Run Genetic Algorithm (GA)
6. Run Particle Swarm Optimization (PSO)
7. Run Tornado Optimization with Coriolis (TOC)
8. Compare optimization performance
9. Analyze convergence and aerodynamic results
10. Evaluate the final optimized wing design

## Evaluation

The optimization results are analyzed using:

- Lift-to-drag ratio (L/D)
- Lift coefficient
- Drag coefficient
- Objective/fitness value
- Convergence behavior
- Final optimized wing parameters

## Technologies

- Python
- NumPy
- SciPy
- Pandas
- Matplotlib
- OpenMDAO
- OpenAeroStruct

## Repository Contents

```text
Aircraft-Wing-Optimization-GA-PSO-TOC/
│
├── Aircraft_Wing_Optimization.ipynb
├── README.md
├── requirements.txt
└── .gitignore

How to Run
Clone or download this repository.
Install the dependencies:
pip install -r requirements.txt
Open Aircraft_Wing_Optimization.ipynb using Jupyter Notebook or JupyterLab.
Run the notebook cells sequentially.
Results

The notebook contains the complete implementation and analysis of the three optimization approaches, including convergence plots and aerodynamic performance comparisons.

Author

Keerthana Lakshmanan

Master of Science in Artificial Intelligence
Ajman University, UAE


