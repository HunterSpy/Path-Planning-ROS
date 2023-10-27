# Path Planning Algorithms: Dijkstra and A*

## Overview
This repository contains Python code for path planning using two popular algorithms, Dijkstra and A*. Path planning is a fundamental problem in robotics and artificial intelligence, and these algorithms are widely used for finding the optimal path between two points in a graph or grid.

In this README file, you will find information on how to use the code, an explanation of the algorithms, and details on the structure of the repository.

## Algorithms
### Dijkstra's Algorithm
Dijkstra's algorithm is a widely used algorithm for finding the shortest path between two nodes in a weighted graph. It works by maintaining a priority queue of nodes and continually selecting the node with the lowest distance from the start node until the goal node is reached. This algorithm is guaranteed to find the shortest path in a graph with non-negative edge weights.

### A* Algorithm
A* is an extension of Dijkstra's algorithm that is used for finding the shortest path in a graph with both edge weights and a heuristic function. It combines the advantages of Dijkstra's algorithm and Best-First Search by using a heuristic to prioritize the search. A* is widely used in robotics, video games, and many other applications.

## Usage 
### Launch
Run the simulation, which will spawn the robot in the gazebo
    roslaunch unit2_pp simulation_unit2.launch

Below launch file will open the RViz, then select the 2D Navigation Path
    roslaunch unit2_pp simulation_unit2.launch
