# 8-queens-A*

A* Search algorithm is one of the best techniques used in path-finding and graph traversals.

## A* algorithm has 3 parameters:

g : the cost of moving from the initial cell to the current cell. Basically, it is the sum of all the cells that have been visited since leaving the first cell.

h : also known as the heuristic value, it is the estimated cost of moving from the current cell to the final cell. The actual cost cannot be calculated until the final cell is reached. Hence, h is the estimated cost. We must make sure that there is never an over estimation of the cost.

f : it is the sum of g and h. So, f = g + h

The way that the algorithm makes its decisions is by taking the f-value into account.
The algorithm selects the smallest f-valued cell and moves to that cell. This process continues until the algorithm reaches its goal cell.
 
The 8 queens problem using A* search algorithm finds the best heuristic way to put eight queens on an 8×8 chessboard such that none of them attack one another (no two are in the same row, column, or diagonal).

The heuristic is calculated by finding g and h costs(here each path cost is 1,hence total cost is 8).
