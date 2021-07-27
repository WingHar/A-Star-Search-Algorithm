# A-Star-Search-Algorithm
A visual implementation of the A-Star Search Algorithm conducted in Python using Manhattan traversal.

This A* Search Algorithm is implemented using Python and Pygame. In order to run it, please install both.
The algorithm utilizes Manhattan distance which is linear traversal. This means it will always go either right or left but never diagonal. 
To begin the algorithm, your first button press indicates the starting node and the second button press indicates the target node.
Once selected, you can click or drag the left mouse button over the grid and place 'black obstacle nodes' around to obstruct the path from the start to the target.
Once you are satisfied, you can hit spacebar to begin the program and watch the algorithm!

A* Search Algorithm
-------------------
The A* Search Algorithm is an effective searching algorithm which finds the shortest path utilizing two parameters, g(n) and h(n). H(n) is the heuristic and g(n) is the edge cases. 
The formula used is F(n) = G(n) + H(n).
F(n) is the total number of edge cases required to go from the starting node to the final node.
G(n) is the number of edge cases from one node to to the next.
H(n) is the estimated number of edge cases to go from the starting node to the ending node.
