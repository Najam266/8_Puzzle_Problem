# 8_Puzzle_Problem
This Repository presents a comparative analysis of four search algorithms used to solve the 8-puzzle problem: Breadth-First Search (BFS), Depth-First Search (DFS), Iterative Deepening Search (IDS), and Uniform Cost Search (UCS). 
8-Puzzle Solver using Search Algorithms
# 8-Puzzle Solver using Search Algorithms  

## Overview  
This project implements four search algorithms—**Depth-First Search (DFS), Breadth-First Search (BFS), Iterative Deepening Search (IDS), and Uniform Cost Search (UCS)**—to solve the **8-puzzle problem**. The program takes an initial state and a goal state as input and finds the steps required to solve the puzzle.  

## Features  
- **Solves the 8-puzzle problem** using DFS, BFS, IDS, and UCS.  
- **Compares algorithm performance** based on:
  - Number of nodes visited  
  - Path cost  
  - Memory usage  
  - Execution time  
- **Visual representation of comparison** using Plotly graphs.  

## Input Format  
The program expects the initial and goal states in **row-major order** as a single string input (e.g., `120345678`).  

## Output Format  
- The sequence of moves required to reach the goal state.  
- Performance metrics for each algorithm.  

## Setup & Installation  
### Prerequisites  
- Python 3.x  
- Jupyter Notebook  
- Required libraries: `numpy`, `collections`, `heapq`, `plotly`  

### Installation Steps  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/8-puzzle-solver.git
   cd 8-puzzle-solver

2.Install dependencies:
 pip install numpy plotly

3.Run the Jupyter Notebook:

 jupyter notebook AI_assignment.ipynb

## Algorithms Implemented
1. Breadth-First Search (BFS)
Explores nodes level by level.
Guarantees the shortest path but uses more memory.
2. Depth-First Search (DFS)
Explores as deep as possible before backtracking.
Memory-efficient but may not find the shortest path.
3. Iterative Deepening Search (IDS)
Combines BFS and DFS by incrementally increasing depth.
Ensures optimality while managing memory efficiently.
4. Uniform Cost Search (UCS)
Expands the least costly node first.
Guarantees the optimal solution.

## Performance Comparison
The project includes a comparison table and bar charts to analyze the performance of all algorithms based on:

Time taken
Path cost
Nodes visited
Memory usage
Results

The results are available in the Word document included in the repository (Comparison_Report.docx).

## Contributors
Najam Ul Islam Saeed