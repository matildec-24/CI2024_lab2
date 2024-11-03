# CI2024_lab2
This repository contains Lab 2, which addresses the Traveling Salesman Problem (TSP) using two main algorithms:

**Greedy Algorithm** (Nearest Neighbor): This method starts from an initial city and iteratively visits the nearest unvisited city until the tour is complete. While it provides an approximate solution to the TSP, it prioritizes minimizing distance at each step locally.

**Simulated Annealing with Adaptive Crossover**: Here, an adaptive simulated annealing algorithm iteratively improves a population of routes. In the initial generations, a more randomized crossover method is used to enhance exploration. As the process continues, an inverse-order crossover is applied, which retains more structural information from parent routes to refine the search for optimal paths.
