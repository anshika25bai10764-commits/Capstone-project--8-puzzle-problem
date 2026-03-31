Here’s a README.md for your 8 Puzzle Problem Capstone Project 
**8 Puzzle Problem Solver**

**Project Overview**
The 8 Puzzle Problem is a classic problem in Artificial Intelligence where a 3×3 grid contains 8 numbered tiles and one empty space. The goal is to move the tiles until they match a predefined goal state.
This project implements an intelligent solver using search algorithms to find the optimal path from the initial state to the goal state.


** Objectives**
Understand and implement AI search algorithms
Solve the 8 puzzle problem efficiently
Compare different search strategies
Visualize the solution path


 **Technologies Used**
Programming Language: Python / Java / C++ (choose yours)
Concepts:
Artificial Intelligence
Search Algorithms
State Space Representation


**Algorithms Implemented**
Breadth-First Search (BFS)
Depth-First Search (DFS)
A* Search Algorithm
Greedy Best-First Search (optional)


** Problem Description**
Initial State :

1 2 3
4 0 5
6 7 8
Goal State:

1 2 3
4 5 6
7 8 0
0 represents the empty space
Tiles can move up, down, left, or right


**How It Works**
Take an initial puzzle configuration
Apply selected search algorithm
Generate possible moves
Evaluate states using heuristics (for A*)
Reach the goal state
Display steps and path


**Heuristics Used (for A*)**
Manhattan Distance
Misplaced Tiles


** How to Run**
Step 1: Clone Repository
Bash
git clone https://github.com/your-username/8-puzzle-solver.git
cd 8-puzzle-solver
Step 2: Run the Program
Bash
python main.py


** Output**
Solution path
Number of moves
Time taken
Nodes explored


**Project Structure**

8-puzzle-solver/
│── main.py
│── solver.py
│── utils.py
│── README.md

**Features**
Multiple search algorithms
Efficient state representation
Heuristic-based optimization
Easy-to-understand output


** Limitations**
High memory usage for BFS
DFS may not find optimal solution
Performance depends on initial state
Future Enhancements
GUI-based visualization
Larger puzzles (15-puzzle)
Performance comparison graphs


** Author**
Anshika Singh
