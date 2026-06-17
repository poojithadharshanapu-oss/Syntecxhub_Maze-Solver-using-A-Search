# Maze Solver using A* Search

## Overview

This project demonstrates the implementation of the A* (A-Star) Search Algorithm to solve a maze efficiently. The algorithm uses a heuristic function (Manhattan Distance) to estimate the cost from the current node to the goal, enabling faster pathfinding compared to uninformed search methods.

## Features

* A* Search Algorithm Implementation
* Manhattan Distance Heuristic
* Automatic Maze Generation
* Shortest Path Calculation
* Graphical Maze Visualization
* Path Length Display
* Efficient Pathfinding

## Technologies Used

* Python
* Pyamaze
* Priority Queue (heap-based search)

## How It Works

1. Generate a maze using the Pyamaze library.
2. Define the start and goal positions.
3. Apply the A* Search Algorithm.
4. Calculate heuristic values using Manhattan Distance.
5. Explore nodes based on the lowest estimated cost.
6. Trace and visualize the shortest path.

## Installation

```bash
pip install pyamaze
```

## Run the Project

```bash
python maze_solver.py
```

## Output

* Generates a random maze.
* Finds the shortest path using A* Search.
* Displays the path graphically.
* Shows the path length.

## Applications

* Robotics Navigation
* Game AI Pathfinding
* GPS Route Optimization
* Autonomous Systems
* Artificial Intelligence Search Problems

## Author

Poojitha Darshanapu
