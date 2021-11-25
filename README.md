# Maze Generator

---


Maze Generator built in JavaScript using the randomized depth-first search algorithm and the recursive backtracker. 


## Description

---

- You can generate randomized mazes depending on how big you want them by selecting the size of it and numbers of columns and rows. It also has a visual representation of how it's being created.

## How it works

---

- Consider the space for a maze being a large grid of cells (like a large chess board), each cell starting with four walls.
- Starting from the top left cell, the program then selects a random neighbouring cell that has not yet been visited. 
- The program removes the wall between the two cells and marks the new cell as visited, and adds it to the stack to facilitate backtracking. 
- The program continues this process, with a cell that has no unvisited neighbours being considered a dead-end.
- When at a dead-end it backtracks through the path until it reaches a cell with an unvisited neighbour, continuing the path generation by visiting this new, unvisited cell (creating a new junction). 
- This process continues until every cell has been visited, causing the program to backtrack all the way back to the beginning cell. We can be sure every cell is visited.


# Maze generation visual

---

![Alt Text](https://media.giphy.com/media/CbNIOqRJaHQ1F4cSgS/giphy.gif)


