# Topics

## Tree Walking

[Tree Traversal Article](https://www.issacc.com/binary-tree-traversal-preorder-inorder-postorder/)

**Preorder Traversal**

![Preorder Traversal](https://s3.amazonaws.com/issac-ghost/2019/03/preorder-traversal.gif)

**Inorder Traversal**

![Inorder Traversal](https://s3.amazonaws.com/issac-ghost/2019/03/inorder-traversal.gif)

**Postorder Traversal**
![Postorder Traversal](https://s3.amazonaws.com/issac-ghost/2019/03/postorder-traversal.gif)


## Ops to Count ?

I have no idea what this is for

## `t(n)` to Big(O)

[Stackoverflow Article](https://stackoverflow.com/questions/15036919/tn-converting-to-on)

- [T(n) means](https://stackoverflow.com/questions/13618183/what-does-the-notation-tn-mean) &rarr; This notation refers to the maximum amount of time (or, more specifically, steps) that a function takes to run.

## Growth Case

[Growth of a Function](https://www.codesdope.com/course/algorithms-growth-of-a-function/)

- The highest order term matters. Such term will outgrow the other one.
- Please refer to [this document](https://github.com/JaredDyreson/university/blob/master/4/Fall/CS-335/notes/chapter-2/Big-Notation-Notes.pdf) for graphs
- Omega (&Omega;): does the function on the **left** supersede the function on the **right**?
    - <img src="https://latex.codecogs.com/svg.latex?\large&space;5n^2 = \Omega(n)" title="Example" />
- Theta (&Theta;): does the function on the **right** supersede the function on the **left**?
    - <img src="https://latex.codecogs.com/svg.latex?\large&space;\frac{n^2}{2} - \frac{n}{2} = \Theta(n^2)" title="Example" />

## Graph Terms

[Definitions in Graph Theory](https://www.statisticshowto.com/graph-theory/)

**Directed Graph**

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a2/Directed.svg/1200px-Directed.svg.png" alt="drawing" width="200"/>

**Simple Graph**

![Graphs Example](https://www.geeksforgeeks.org/wp-content/uploads/undirectedgraph.png)


**Weighted Graph**

<img src="https://ucarecdn.com/a67cb888-aa0c-424b-8c7f-847e38dd5691/" alt="drawing" width="200"/>

### Terms

- Arc: directed line (a pair of ordered vertices)
- Edge: connection to the node
    * Incident edges: share a vertex
- Loop: arc that joins a vertex itself
- Vertex: entity in the graph (node)
    * Adjacent: vertices which are connected by an edge
    * Degree: number of edges that feed into a node
    * Predecessor: before a given vertex on a path
    * Successor: vertex following a given vertex on a path
- Walk: series of vertices and edges
    * Circuit: closed walk with every distinct edge distinct
    * Closed walk: a walk from a vertex back to itself; a series of vertices and edges which begins and ends at the same place
    * Cycle: closed walk without any repeated vertices (except that of the first and last vertices are the same)
    * Path: walk where no repeated vertices. A `u-v` path is a path beginning at `u` and ending at `v`.
    * `u-v` walk: would be a walk beginning at `u` and ending at `v`

## Planar

The conversion from a three dimensional representation to a planar one (R^2)

**Three Dimensions**

<img src="https://upload.wikimedia.org/wikipedia/commons/e/e0/Dodecahedron.jpg" alt="drawing" width="200"/>


**Two Dimensions**

<img src="https://www.researchgate.net/profile/Pawel_Pralat/publication/260124998/figure/fig1/AS:614235851743237@1523456647768/A-plane-representation-of-the-dodecahedron.png" alt="drawing" width="200"/>

## Euler Konigsberg Bridge Problem

- Please refer to [this document](https://github.com/JaredDyreson/university/blob/master/4/Fall/CS-335/notes/chapter-1/submission.md) for more details

## Hamiltonian Cycle

Undirected or directed graph that visits each node exactly one time

**Example**

<img src="https://www.statisticshowto.com/wp-content/uploads/2017/11/hamiltonian.png" alt="drawing" width="200"/>

## Adjacency Matrix

<img src="https://mathworld.wolfram.com/images/eps-gif/AdjacencyMatrix_1002.gif" alt="drawing" width="400"/>

A square matrix used to represent a finite graph. The elements of the matrix indicate whether pairs of vertices are adjacent or not in the graph. In the special case of a finite simple graph

## Master Theorem

**Video Explanation**

[![](http://img.youtube.com/vi/2H0GKdrIowU/0.jpg)](http://www.youtube.com/watch?v=2H0GKdrIowU "Master Theorem")

![Equation](assets/master-theorem.png)

### Examples

- ![Example 1](assets/master-theorem-example-1.png)
=====================================================
- ![Example 2](assets/master-theorem-example-2.png)
=====================================================
- ![Example 3](assets/master-theorem-example-3.png)

## Sorting Algorithms

Please refer to [this document](https://github.com/JaredDyreson/university/blob/master/4/Fall/CS-335/notes/chapter-3/Chapter-3.md) for more information

## Gauss' Trick

Please read [this article](https://nzmaths.co.nz/gauss-trick-staff-seminar) for more information

## Brute Force Searching

**Directly pulled from Siska's notes**

- Pattern: Length => K
- String: Length => N
- Representation
    * Array of characters
- Algorithm: test each next spot
    * Does pattern match?
- Pass: Each pattern char
- Solution: N passes
- Analyze: `T(N) = # of passes T(passes)` &rarr; `O(n)`

## Traveling Salesperson (TSP)

**Video Explanation**

[![](http://img.youtube.com/vi/cY4HiiFHO1o/0.jpg)](http://www.youtube.com/watch?v=cY4HiiFHO1o "Traveling Salesman")

- Problem: Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city exactly once and returns to the origin city
- *NP-hard*: defining property of a class of problems that are informally "at least as hard as the hardest problems in NP". A simple example of an NP-hard problem is the subset sum problem.

## Depth First Search

<img src="https://upload.wikimedia.org/wikipedia/commons/7/7f/Depth-First-Search.gif" alt="drawing" width="200"/>

[Explanation of DFS](https://www.educative.io/edpresso/how-to-implement-depth-first-search-in-python)

## Breadth First Search

<img src="https://upload.wikimedia.org/wikipedia/commons/4/46/Animated_BFS.gif" alt="drawing" width="200"/>

[Explanation of DFS](https://www.hackerearth.com/practice/algorithms/graphs/breadth-first-search/tutorial/)

## TODO

- Back substitution trick
