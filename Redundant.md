## Redundant Connection

### Problem Tree
In this problem, a **tree** is an undirected graph that is connected and has no cycles.

You are given a graph that started as a tree with `n` nodes labeled from `1` to `n`, with one additional edge added. The added edge has two different vertices chosen from `1` to `n`, and was not an edge that already existed. The graph is represented as an array `edges` of length `n` where `edges[i] = [a_i, b_i]` indicates that there is an edge between nodes `a_i` and `b_i` in the graph.

Your task is to return an edge that can be removed so that the resulting graph is a tree of `n` nodes. If there are multiple answers, return the answer that occurs **last** in the input.

### Constraints
- `n == edges.length`
- `3 <= n <= 1000`
- `edges[i].length == 2`
- `1 <= a_i < b_i <= edges.length`
- `a_i != b_i`
- There are no repeated edges.
- The given graph is connected.

### Input
- An array of edges `edges` of length `n`, where `edges[i] = [a_i, b_i]` represents an undirected edge between nodes `a_i` and `b_i`.

### Output
- Return the edge `[a, b]` that can be removed to make the graph a tree. If there are multiple answers, return the edge that occurs last in the input.

### Example
![](redundant-graph)
#### Input:
```bash
edges = [[1,2], [1,3], [2,3]]
```

#### Input:
```bash
[2,3]
```
