# Genetic Algorithm for N-Queens Problem

This project implements a genetic algorithm to solve the N-Queens problem, which involves placing N queens on an NxN chessboard such that no two queens attack each other.

## Overview

The genetic algorithm consists of the following components:
- **Population Generation**: Generates an initial population of possible solutions.
- **Crossover**: Combines two parent solutions to produce offspring.
- **Mutation**: Randomly alters an offspring solution to introduce diversity.
- **Fitness Evaluation**: Evaluates how close a solution is to the goal.
- **Selection**: Selects the best solutions to produce the next generation.

## Implementation Details

### Parameters
- `n`: The size of the chessboard (number of queens).

### Functions

#### `generatePopulation()`
Generates an initial population of possible solutions.

#### `crossover(parent1, parent2)`
Combines two parent solutions to produce two offspring.

#### `mutation(parent)`
Randomly alters a solution to introduce diversity.

#### `fitness(chromosome)`
Evaluates the fitness of a solution, which is a measure of non-attacking queens.

#### `Selection(Population)`
Selects the best solutions to produce the next generation.

### Main Execution Flow
1. **Generate Initial Population**: Uses `generatePopulation()` to create the initial set of solutions.
2. **Evaluate Fitness**: Uses `Probabilities()` to calculate the fitness of each solution.
3. **Selection and Crossover**: Uses `Selection()` to select the best solutions and `crossover()` to produce new solutions.
4. **Mutation**: Uses `mutation()` to introduce diversity.
5. **Repeat**: The process repeats until a solution with the maximum fitness is found.

## Usage

To run the genetic algorithm, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone <[repository-url](https://github.com/ridaamirr/N-Queens-Problem/)>
    ```

2. **Run the Script**: Execute the Python script to generate the initial population, perform selection, crossover, and mutation, and find a solution to the N-Queens problem.


