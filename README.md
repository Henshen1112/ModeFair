# Vehicle Routing Problem with Genetic Algorithm
![image](https://github.com/Henshen1112/vehicle_routing_problem/assets/117999447/51e99e17-ca7b-4894-9cc9-68b3e2dbb6fb)

This task implements a Genetic Algorithm (GA) to solve the Vehicle Routing Problem (VRP), optimizing routes for a fleet of vehicles to minimize total distance traveled and associated costs.

## Problem Description
The Vehicle Routing Problem involves finding optimal routes for a fleet of vehicles to serve a set of customers, with each customer having a demand to be fulfilled. The objective is to minimize the total distance traveled by the vehicles while satisfying all customer demands and considering vehicle capacity constraints.

## Implementation Details
- Python is used to implement the genetic algorithm.
- The GA involves initializing a population of solutions, evaluating their fitness, selecting top-performing individuals, and performing crossover and mutation to create offspring for the next generation.
- The fitness function calculates the total cost of a solution, considering the distances traveled by each vehicle and associated costs.
- The code includes helper functions for calculating distances, generating initial populations, performing crossover and mutation, and repairing routes.
