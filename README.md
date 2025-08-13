# Project 3 – Graph Modeling and Graph Algorithms  
**COT 4400, Spring 2025**  
**Due:** May 7, 2025  

## Overview  
This project solves the **"Jumping Jim"** maze problem by modeling it as a **graph** and applying a **graph search algorithm** to determine a valid path from the starting square (top-left) to the goal square (bottom-right).  

In the maze, each square contains an integer that indicates the exact number of spaces Jim must move **horizontally** or **vertically** (not diagonally) when bouncing off that trampoline. The challenge is to determine a sequence of moves that leads to the goal.  

---

## Problem Summary  
- **Vertices:** Each square in the maze.  
- **Edges:** Possible moves from a square, determined by the integer value in that square (jump distance).  
- **Goal:** Reach the bottom-right square.  
- **Allowed Moves:** N (north), E (east), S (south), W (west).  

Example start:  
- From `(0,0)` with value `3`, you could move three spaces down or three spaces right.  

---

## Input Format  
The program reads **`input.txt`** with the following format:  


Where:  
- `r` = number of rows in the maze  
- `c` = number of columns in the maze  
- Each `aij` = number of spaces Jim will move from that square  

---

## Output Format  
The program writes to **`output.txt`** a **single line** containing the sequence of moves (N, E, S, W) separated by spaces.  
Example:  
Means:  
1. Move 3 spaces right  
2. Move 3 spaces down  
3. Move 2 spaces right  

---

## Compilation & Execution  
### **Java**
javac *.java
java JumpingJim

## License 
Copyright (c) 2025 Shasha Alvares

All Rights Reserved.

This project and its contents may not be copied, modified, distributed, or used in any way without explicit written permission from the author. 
This code was created for an academic assignment and is not licensed for public or commercial use.
