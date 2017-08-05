# astar_shortest_path
This prolog program implements the A* (a star) algorithm. It finds the path between two cities that is the shortest and has less number of nodes (vertices)

Given a graph that represents the problem of shortest path, where nodes are cities and edges are roads, the program finds the best path.

How to run the program with SWI-Prolog?

?- find_shortest_path('City A','City E').

output:

The best/shortest Path is: City A, City B, City E 
The total cost of the path is: 521 kilometers.
Highway to be traveled will be: N 163 - N 163

true

Note: The code was adapted from: https://github.com/nicodelpiano/astar-algorithm/blob/master/a_star.pl




