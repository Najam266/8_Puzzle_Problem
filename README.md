# 8-Puzzle Problem Solver

This repository presents a **comparative analysis** of four search algorithms used to solve the **8-puzzle problem**:  
- **Breadth-First Search (BFS)**  
- **Depth-First Search (DFS)**  
- **Iterative Deepening Search (IDS)**  
- **Uniform Cost Search (UCS)**  

## Overview  

The **8-puzzle problem** consists of a **3×3 grid** with **8 numbered tiles** and **one blank space**. The goal is to **rearrange** the tiles to match a given **goal state** by moving the blank space.  

This project **implements and compares** four search algorithms in terms of:  
- Number of **nodes visited**  
- **Path cost**  
- **Memory usage**  
- **Execution time**  

It also includes **Plotly visualizations** for performance comparison.  

## Features  

✔️ **Solves the 8-puzzle problem** using BFS, DFS, IDS, and UCS.  
✔️ **Displays the solution path** step by step.  
✔️ **Compares performance metrics** in a tabular and graphical format.  

## Input Format  

The program expects the **initial and goal states** as **row-major order strings** (e.g., `"120345678"`).  

### Example Input  
```
Enter start state: 120345678  
Enter goal state: 012345678  
```

## Output Format  

- **Sequence of moves** to reach the goal state.  
- **Performance metrics** for each algorithm.  
- **Comparison graph** using Plotly.  

### Example Output  
```
-----------------
BFS Algorithm
-----------------
Time Taken: 0.001004 seconds
Path Cost: 2
Nodes Visited: 3
```

## Setup & Installation  

### Prerequisites  
Make sure you have the following installed:  
- **Python 3.x**  
- **Jupyter Notebook**  
- Required libraries: `numpy`, `collections`, `heapq`, `plotly`  

### Installation Steps  

```bash
# Clone the repository
git clone https://github.com/yourusername/8-puzzle-solver.git
cd 8-puzzle-solver

# Install dependencies
pip install numpy plotly

# Run the Jupyter Notebook
jupyter notebook AI_assignment.ipynb
```

## Algorithms Implemented  

### 1️⃣ Breadth-First Search (BFS)  
✔ Explores nodes **level by level**.  
✔ Guarantees the **shortest path** but requires **more memory**.  

### 2️⃣ Depth-First Search (DFS)  
✔ Explores **as deep as possible** before backtracking.  
✔ **Memory-efficient**, but may not find the **shortest path**.  

### 3️⃣ Iterative Deepening Search (IDS)  
✔ Combines BFS and DFS by **incrementally increasing depth**.  
✔ Ensures **optimality** while managing **memory efficiently**.  

### 4️⃣ Uniform Cost Search (UCS)  
✔ Expands the **least costly node** first.  
✔ **Guarantees** the **optimal solution**.  

## Performance Comparison  

This project includes a **comparison table and bar charts** to analyze performance based on:  
- **Time Taken**  
- **Path Cost**  
- **Nodes Visited**  
- **Memory Usage**  

📌 **Results are available in** `Comparison_Report.docx`.  

## Contributor  

**Najam Ul Islam Saeed**  


