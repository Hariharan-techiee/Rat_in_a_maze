# Rat-in-a-Maze-Using-Backtracking

## Introduction
This repository provides an implementation of the Rat Maze algorithm, a pathfinding algorithm designed to solve mazes efficiently. The algorithm employs a depth-first search approach with backtracking to find the optimal path from the starting point to the destination in a maze.

## Algorithm Overview
The `rat_maze` function in this repository utilizes C Graphics to visualize the maze-solving process. It incorporates a stack data structure to keep track of visited cells and backtracks when necessary.

## Procedure Steps
1. **Initialization:** Initialize variables and necessary data structures.
2. **Define Moves:** Define possible moves in the maze matrix.
3. **Mark Cells:** Mark cells in the maze as visited.
4. **Exploration Loop:** Start exploring the maze using a while loop until the destination is reached or no solution is found.
   - If a valid move is available and not visited, proceed to the next cell.
   - If the destination is reached, print "Goal Reached" and exit the loop.
   - If no valid move is available, backtrack to the previous cell.
5. **Path Printing:** Print the path taken by the algorithm.
6. **Solution Check:** If the maze has no solution, print "Solution does not exist".

## Output Legend
- **WHITE:** Backtracking
- **PURPLE:** Path
- **GREEN:** Blocks
- **YELLOW:** Start and Destination

## Output Visualization
![image](https://github.com/Kaviyarasu-S007/Rat-in-a-Maze/assets/151661034/37978825-b075-45a8-bdd0-edbb62ea62b4)
![image](https://github.com/Kaviyarasu-S007/Rat-in-a-Maze/assets/151661034/3b2d67d8-5532-4703-ab0e-7250de711cfd)


Feel free to explore the code and visualize the maze-solving process with this algorithm. If you encounter any issues or have suggestions, please don't hesitate to contribute or reach out.
