## All Paths From Source to Target

### Problem Statement
Given a **directed acyclic graph (DAG)** of `n` nodes labeled from `0` to `n - 1`, find all possible paths from **node 0** to **node n - 1** and return them in any order.

The graph is represented as: `graph[i]` is a list of all nodes you can visit from node `i` (i.e., there is a directed edge from node `i` to node `graph[i][j]`).

### Constraints:
- `n == graph.length`
- `2 <= n <= 15`
- `0 <= graph[i][j] < n`
- `graph[i][j] != i` (i.e., there will be no self-loops)
- All the elements of `graph[i]` are unique.
- The input graph is guaranteed to be a **DAG** (Directed Acyclic Graph).

### Example:

#### Input:
```plaintext
 graph = [[4,3,1],[3,2,4],[3],[4],[]]
```

#### Output:
```plaintext
 [[0,4],[0,3,4],[0,1,3,4],[0,1,2,3,4],[0,1,4]]
```
