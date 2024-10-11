## Validate Binary Search Tree

### Problem Statement:
There are `n` cities. Some of them are connected, while some are not. If city `a` is connected directly with city `b`, and city `b` is connected directly with city `c`, then city `a` is connected indirectly with city `c`.

Given the root of a binary tree, determine if it is a valid **binary search tree (BST)**.

A **valid BST** is defined as follows:
- The left subtree of a node contains only nodes with keys **less than** the node's key.
- The right subtree of a node contains only nodes with keys **greater than** the node's key.
- Both the left and right subtrees must also be binary search trees.

### Constraints:
- The number of nodes in the tree is in the range `[1, 10^4]`.
- `-2^31 <= Node.val <= 2^31 - 1`

### Example:
![](Tree.jpg)
**Input**: 
```plaintext
root = [2,1,3]
```

**Output**: 
```plaintext
true
```

