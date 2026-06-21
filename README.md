# Intro to AI Search Lab (Part A & B)

## Overview
This project implements classic AI search algorithms for grid-based pathfinding problems.  
It compares different search strategies and heuristics on both standard and weighted grids.

---

## Algorithms Implemented

### Part A (Uninformed + Basic Heuristics)
- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- Uniform Cost Search (UCS)

### Part B (Informed Search)
- Greedy Best-First Search
- A* Search
- Weighted A*
- Iterative Deepening Search (if included in your lab)

---

## Heuristics Used
- Manhattan Distance
- Euclidean Distance
- Zero Heuristic (for UCS behavior)
- Inflated Heuristic (weighted A*)

---

## Grid Environment
The environment is a 2D grid where:
- `0` = free space
- obstacles or terrain costs may apply in weighted maps

Weighted maps include terrain costs that affect path cost during search.

---

## How to Run

Run the main notebook or script provided in the lab:

```bash
python main.py
