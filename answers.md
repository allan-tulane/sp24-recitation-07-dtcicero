# CMPS 2200 Recitation 10## Answers

**Name:** Daniel Cicero
**Name:**_________________________


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**
-  Given n nodes and m edges, the work of reachable is O(n + m) The worst case arises in a graph in which all nodes are connected to each other.


- **4)**
- Given n nodes in a graph, the worst case number of times we would have to call reachable is n times.  

- **5)**
- Assuming n nodes and m edges, the work of connected is O(n+m)

- **7)**
- Switching from a map of neighbors (adjacency list) to an adjacency matrix would indeed affect the work complexity of the reachable function. This is because in the adjacency list, checking for neighbors can be accomplished by iterating over the neighbors of each node. As each node can have a maximum of n neighbors, the work is O(m) + and additional step of O(n) for initialization for a total of O(n + m) work. By contrast, the adjacency matrix represents neighbors as an n * n matrix, and therefore requires O(n^2) work to initialize. Neighbor exploration in the adjacency matrix can be done in constant time, but iterating over all neighbors of a node still takes O(n) time due to the number of entries in the row corresponding to that node.
