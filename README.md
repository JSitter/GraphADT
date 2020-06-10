# Homework 1: Graph ADT & Traversals

Follow the instructions [here](https://make-school-courses.github.io/CS-2.2-Graphs-Recursion/#/Assignments/01-Graph-ADT) to complete this assignment.

## Discussion Questions

1. How is Breadth-first Search different in graphs than in trees? Describe the differences in your own words.

One of the differences between BFS search between graphs and trees is that trees may not have cycles whereas graphs may. In order to prevent an infinite loop while traversing a graph you will need to keep track of the vertices that have been visited.

2. What is one application of Breadth-first Search (besides social networks)? Describe how BFS is used for that application. If you need some ideas, check out [this article](https://www.geeksforgeeks.org/applications-of-breadth-first-traversal/?ref=rp).

Breadth first search is good for checking to see if a graph is biparite, that is each node is connected to a node of a different color than the current one.
