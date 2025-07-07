# 🧠 Maze Solver Visualization: BFS, DFS, and A\*

This project demonstrates the visualization of pathfinding algorithms (BFS, DFS, and A\*) solving a 2D maze using `matplotlib`. It's designed for educational purposes, showing how different search strategies explore the maze and find the goal.

---

## ✨ Features

- Visualizes the step-by-step process of:
  - **Breadth-First Search (BFS)**
  - **Depth-First Search (DFS)**
  - **A\* Search (with Manhattan heuristic)**
- Maze displayed using `matplotlib`
- Animated cell-by-cell exploration
- Logs:
  - Path length
  - Steps taken
  - Total visited nodes
  - Execution time

---

## 🧩 Maze Format

The maze is defined as a 2D list:

- `'S'` — Start
- `'G'` — Goal
- `0` — Free cell
- `1` — Wall
