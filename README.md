# 8-Puzzle-Solver
Uses A* search, BFS, and DFS to solve the 8-puzzle.

Puzzle states are inputted as an array representing the configuration, e.g. [0,1,2,3,4,5,6,7,8]
0 represents the empty tile, so the above example is the goal state. 

A* search uses the sum of each tile's manhattan distance to its goal location as its hueristic. 
