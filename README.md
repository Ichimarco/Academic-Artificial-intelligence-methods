# Academic Artificial Intelligence Methods

This repository contains academic projects developed as part of the Artificial Intelligence Methods course. The collection covers various AI techniques, ranging from classical graph search algorithms to evolutionary computing, swarm intelligence, and fuzzy logic systems.

## Table of Contents
* [Traveling Salesman Problem (TSP)](#traveling-salesman-problem-tsp)
* [Particle Swarm Optimization (PSO)](#particle-swarm-optimization-pso)
* [Fuzzy Logic Systems](#fuzzy-logic-systems)
* [Requirements and Usage](#requirements-and-usage)

---

## Traveling Salesman Problem (TSP)
The first part of the course focuses on solving the TSP in a 3D space using various search and optimization strategies.

| File | Technique | Description |
| :--- | :--- | :--- |
| `TSP_Graph_Search.ipynb` | **Uninformed Search** | Implementation and time complexity analysis of Breadth-First Search (BFS) and Depth-First Search (DFS). |
| `TSP_AStar_Greedy.ipynb` | **Greedy Search** | Implementation of the Greedy Nearest Neighbor algorithm and a Greedy approach based on Minimum Spanning Tree (MST). |
| `TSP_AStar_Heuristics_Comparison.ipynb` | **Informed Search (A*)** | Solving TSP using the A* algorithm with a comparison between admissible (MST-based) and inadmissible heuristics. |
| `TSP-Genetic-Algorithm.ipynb` | **Metaheuristics** | Advanced optimization using Ant Colony Optimization (ACO) compared against classical search methods. |

---

## Particle Swarm Optimization (PSO)
The project in `PSO_Global_Optimization_Beale_Function.ipynb` demonstrates transition from discrete to continuous optimization.

* **Objective**: Finding the global minimum of the Beale Function.
* **Method**: Implementation of the Particle Swarm Optimization algorithm.
* **Key Features**: Analysis of inertia weight, cognitive weight, and social weight on swarm convergence.

---

## Fuzzy Logic Systems
The project in `Fuzzy_Logic_Projectile_Motion_Controller.ipynb` explores fuzzy inference systems for modeling physical phenomena.

* **Problem**: Estimating the initial velocity of a projectile based on projection angle, distance, air resistance, and mass.
* **Implementation**: Definition of fuzzy antecedents, consequents, and a Mamdani-style rule base.
* **Results**: Comparative analysis between the fuzzy model and theoretical physics calculations (with and without air resistance).

---

## Requirements and Usage

### Dependencies
To run these notebooks, the following Python libraries are required:
* NumPy
* Matplotlib
* NetworkX
* Scikit-fuzzy
* Scikit-learn

### Installation
```bash
pip install numpy matplotlib networkx scikit-fuzzy scikit-learn
