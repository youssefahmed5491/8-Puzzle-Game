8 Puzzle Game

This is a fun game in which the user enters a board like 120345678
Then chooses the algoriithm to shift the board till it reach 012345678 
The a algoriithm 1 for BFS , 2 for DFS , 3 for A* first hierc , 4 for A* second hierc
	-BFS is Breadth-first search which means the algo will first try the four posible boards resulting from the current board which means moving right , or left , or up , or down
	-DFS is Depth-first search which means the algo will first try the every posible boards resulting from the current board till it reaches the final board this result in worst solution because the algo will keep going even if it reaches an infinite loop
	-A* first hierc similar to BFS but using priority queue which calculate f(n) which is equal to h(n)= abs(current_cell:x - goal:x) + abs(current_cell:y - goal:y) plus g(n) which is the cost of rreaching the current board from the start board
	-A* second hierc same as first hierc but h(n)= sqrt((current_cell:x - goal:x)2 + (current_cell.y - goal:y)2)
After runing the program will return 
	-The expanded nodes which is the tree of the algo
	-The path that the algo choose to reach the final board
	-The Cost which is the number of moves or number of path nodes - 1
	-The execution time in millisecond