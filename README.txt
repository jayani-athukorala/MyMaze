Maze Solver Programs
---------------------------------------
This repository contains three Python programs that use different algorithms to solve mazes. The implemented algorithms include Breadth-First Search (BFS), Depth-First Search (DFS), and Genetic Algorithms. These programs are designed to solve mazes efficiently, and the algorithms are flexible enough to work with various maze configurations.

Maze Representation:
-------------------
The mazes are represented as 2D arrays, where:

	0 indicates walls,
	1 indicates available paths,
	3 indicates the entrance,
	2 indicates the destination.
This allows for the flexibility of placing the initial source and destination anywhere within the maze.

Implemented Algorithms:
----------------------
1. Breadth-First Search (BFS)
The BFS algorithm explores the maze level by level, ensuring the shortest path is found. The corresponding Python program is named bfs_solver.py.

2. Depth-First Search (DFS)
The DFS algorithm explores the maze deeply, backtracking when necessary. The Python program implementing DFS is named dfs_solver.py.

3. Genetic Algorithms
The Genetic Algorithms program (genetic_solver.py) uses an evolutionary approach to find optimal solutions. It evolves a population of potential solutions through generations, selecting the fittest individuals.

GUI for Visualization:
----------------------
To enhance the visualization of maze-solving, a Graphical User Interface (GUI) is created using the Tkinter library. The GUI displays the maze and the movement paths of the algorithms in an animated way.

Usage:
-----
To use these programs, modify the maze in the code or provide a maze as a 2D list to the corresponding solver class. Run the respective Python script to see the algorithm in action. The GUI will display the maze and the solution path.

Feel free to experiment with different mazes and initial source-destination configurations to observe the versatility of the algorithms.

Enjoy exploring and solving mazes!
