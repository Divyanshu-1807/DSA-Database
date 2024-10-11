## Lowest Common Ancestor of a Binary Tree

### Problem Statement:
Given a binary tree, find the **Lowest Common Ancestor (LCA)** of two given nodes in the tree.

According to the definition of LCA:  
“The lowest common ancestor is defined between two nodes `p` and `q` as the lowest node in the tree `T` that has both `p` and `q` as descendants (where we allow a node to be a descendant of itself).”

### Constraints:
- The number of nodes in the tree is in the range `[2, 10^5]`
- `-10^9 <= Node.val <= 10^9`
- All `Node.val` are unique.
- `p` != `q`.
- `p` and `q` will exist in the tree.

### Example:
![](tree2.png)

#### Input:
```plaintext
root = [3, 5, 1, 6, 2, 0, 8, null, null, 7, 4], p = 5, q = 1
```
#### Output:
```plaintext
5
```
**Explanation:** The LCA of nodes 5 and 4 is 5, since a node can be a descendant of itself according to the LCA definition.
