# MAZE-GAME

it's a game, the player (BOY) have to solve a generated maze in order to reach to the GIRL.

the game have many features and have ability to add more.

Features:
* there is a KEY and a GATE, located in some place in the maze BOY should get the KEY first to open the GATE of the square which the GIRL is trapeed in.

- note: oue implementation for node (cell) manage you to add more and more features just by adding more references.

* game generate maze according to prim algorithm.

* there are some kind of help as (solve key) whitch slove the maze as source is BOY and sink is KEY using an apstraction recursion algorithm deal with stack, queue or any data structure to solve the maze, if stack used the apstraction algorithm will act like DFS, if queue used the apstraction algorithm will act like BFS, you can use your own data structure just implement the interface IMazeAlgoro.

* You can also draw your own maze by yourslef, just add .txt and name it some thing like Level#.txt where # is number of level.
- level form:
	first line shoulf have width and hight.
	then start to draw the maze where
	# --> wall
	. --> empty
	S --> source (BOY)
	E --> end (GIRL)
	K --> key
	G --> gate

