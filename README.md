# Knapsack-Based Resource Allocation Using Genetic Algorithm

## Problem Overview
Select laboratory equipment under a fixed budget constraint to maximize total utility without exceeding the capital ceiling.

## Bio-Inspired Computing Setup
- Track: Genetic Algorithms
- Representation: Binary Chromosome Array
- Selection: Tournament Selection with size 3
- Crossover: Single Point Crossover with probability 0.85
- Mutation: Bit Flip Mutation with probability 0.035
- Constraint Handling: Exterior Linear Penalty
- Elitism: Best 2 individuals retained per generation

## Verification Benchmark
An exact 0-1 knapsack dynamic programming algorithm is executed alongside the Genetic Algorithm to verify theoretical optimality.

## Repository Contents
- knapsack_resource_allocation.ipynb: complete Colab notebook
- optimal_lab_allocation.csv: exported tabular equipment procurement schedule
- knapsack_resource_allocation_dashboard.png: 4-panel visual convergence and utilization dashboard
- README.md: project documentation and execution instructions

## How to Run
1. Open the notebook in Google Colab.
2. Execute all cells sequentially.
