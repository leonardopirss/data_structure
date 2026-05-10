# data_structure
BFS and DFS in practice, showing these algorithms in real problems and their efficiency.

## BFS (Breadth-First Search)
BFS explores a graph level by level, visiting all neighbors of a node before moving to the
next level. It uses a queue to keep track of the frontier and guarantees the shortest path
in an unweighted graph. Time complexity is O(V + E), where V is the number of vertices and
E is the number of edges.

## DFS (Depth-First Search)
DFS explores a graph or tree by going as deep as possible along a branch before backtracking.
It uses a stack (explicitly or via recursion) to track the path. It is useful for path
exploration and structure discovery, and runs in O(V + E) time for graphs (or O(N) for trees).
