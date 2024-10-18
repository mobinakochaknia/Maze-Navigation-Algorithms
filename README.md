# Maze Navigation Algorithms

This project explores various search algorithms applied to a randomly generated maze. The algorithms implemented include Depth-First Search (DFS), Breadth-First Search (BFS), and A* Search, both with and without entrance costs for each cell in the maze. The goal is to navigate from a starting position (Pacman) to a goal position (Food) in the maze.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Algorithms](#algorithms)
  - [Depth-First Search (DFS)](#depth-first-search-dfs)
  - [Breadth-First Search (BFS)](#breadth-first-search-bfs)
  - [A* Search](#a-search)
- [Visualization](#visualization)



## Features

- Random maze generation.
- Visualization of the maze, paths taken by each algorithm, and cost of each cell.
- Implementation of DFS, BFS, and A* algorithms.
- Option to add entrance costs to the maze.

## Getting Started

### Prerequisites

To run this project, ensure you have the following installed:

- Python 3.x
- NumPy
- Matplotlib

Running the Project
1. Clone the repository:
git clone https://github.com/yourusername/maze-navigation.git
cd maze-navigation
2. Run the main script:
 python maze_navigation.py


## Usage
After running the script, you will see visualizations of the maze with the paths found by each algorithm. The output will include the number of expanded nodes and the total cost of navigating to the goal.

 ## Algorithms
## Depth-First Search (DFS)
DFS is a graph traversal algorithm that explores as far as possible along each branch before backtracking. In this implementation, DFS is adapted to find the best path with the least entrance cost.

## Breadth-First Search (BFS)
BFS is another graph traversal algorithm that explores all neighbor nodes at the present depth prior to moving on to nodes at the next depth level. It guarantees the shortest path in an unweighted graph.

## A* Search
A* is an informed search algorithm that uses a heuristic to guide its exploration. It maintains a priority queue of nodes to explore, selecting the node with the lowest estimated cost to reach the goal. The heuristic used in this implementation is the Manhattan distance.

## Visualization
The maze and paths are visualized using Matplotlib. Each cell in the maze has an associated entrance cost, which is displayed within the cell. The start (Pacman) and goal (Food) positions are highlighted in different colors.

Red: High cost
Green: Low cost
Orange: Medium cost

