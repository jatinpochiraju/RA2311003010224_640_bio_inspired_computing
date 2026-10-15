# knapsack-based resource allocation using genetic algorithm

## team details
- Name: N V Jatin Pochiraju | RA No: RA2311003010224
- Name: Rajyalaxmi Mishra | RA No: RA2311003010640

## problem overview
Select laboratory equipment under a fixed budget constraint to maximize total utility without exceeding the capital ceiling.

## bio-inspired computing setup
- track: Genetic Algorithms
- representation: binary chromosome array
- selection: tournament selection with size 3
- crossover: single point crossover with probability 0.85
- mutation: bit flip mutation with probability 0.035
- constraint handling: exterior linear penalty
- elitism: best 2 individuals retained per generation

## verification benchmark
An exact 0-1 knapsack dynamic programming algorithm is executed alongside the Genetic Algorithm to verify theoretical optimality.

## repository contents
- knapsack_resource_allocation.ipynb: complete Colab notebook
- optimal_lab_allocation.csv: exported tabular equipment procurement schedule
- knapsack_resource_allocation_dashboard.png: 4-panel visual convergence and utilization dashboard
- README.md: project documentation and execution instructions

## how to run
1. Open the notebook in Google Colab.
2. Execute all cells sequentially.
