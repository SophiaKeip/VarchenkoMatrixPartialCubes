# VarchenkoMatrixPartialCubes

We compute the Varchenko matrix of a partial cube.

The Python script `Calc_VM.py` computes the Varchenko matrix of a given partial cube graph. It is based on a collection of functions from [David Eppstein](https://ics.uci.edu/~eppstein/) and and utilizes symbolic matrix construction provided by the `sympy` library.

**Input:**  
An undirected graph `G`, represented as a dictionary of adjacency lists.

**Output:**

- A symbolic Varchenko matrix representing the graph.  
- A file `VarchenkoMatrix.txt` containing the matrix in comma-separated format.

The script checks whether the input graph is a partial cube. If it is, it identifies the equivalence classes of the Djokovi\'c-Winkler-relation on edges, assigns symbolic variables to them, and constructs the corresponding Varchenko matrix.

This script uses the work of **David Eppstein**.  
In order to use our script, get the following files:

BFS.py
Biconnectivity.py
Bipartite.py
BipartiteMatching.py
DFS.py
Graphs.py
Medium.py
PartialCube.py
PartialOrder.py
StrongConnectivity.py
UnionFind.py
Util.py

from  
[https://ics.uci.edu/~eppstein/PADS/](https://ics.uci.edu/~eppstein/PADS/)
