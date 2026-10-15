# Knapsack-based resource allocation using genetic algorithm

## Team details
- Name: N V Jatin Pochiraju | RA No: RA2311003010224
- Name: Rajyalaxmi Mishra | RA No: RA2311003010640

## Problem overview
Select laboratory equipment under a fixed budget constraint to maximize total utility without exceeding the capital ceiling.

## Bio-inspired computing setup
- track: Genetic Algorithms
- representation: binary chromosome array
- selection: tournament selection with size 3
- crossover: single point crossover with probability 0.85
- mutation: bit flip mutation with probability 0.035
- constraint handling: exterior linear penalty
- elitism: best 2 individuals retained per generation

## Verification benchmark
An exact 0-1 knapsack dynamic programming algorithm is executed alongside the Genetic Algorithm to verify theoretical optimality.

## Repository contents
- `RA2311003010224,640_bio_inspired_computing.ipynb`: complete Google Colab notebook containing code, equations, and visual outputs
- `ra2311003010224,640_bio_inspired_computing.py`: standalone Python source code implementation
- `knapsack_resource_allocation_dashboard.png`: four-panel visual analytics and convergence dashboard
- `optimal_lab_allocation.csv`: exported tabular equipment procurement schedule
- `README.md`: project documentation, team details, and execution guide
- `LICENSE`: project license file
- `.gitignore`: Git configuration for ignored files

## How to run
1. Open the notebook in Google Colab.
2. Execute all cells sequentially.
