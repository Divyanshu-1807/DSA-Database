## Intersection of Two Linked Lists

### Problem Statement:
Given the heads of two singly linked-lists `headA` and `headB`, return the node at which the two lists intersect. If the two linked lists have no intersection at all, return `null`.

The test cases are generated such that there are no cycles anywhere in the entire linked structure.

**Note** that the linked lists must retain their original structure after the function returns.

**Custom Judge**:

The inputs to the judge are given as follows (your program is not given these inputs):

- `intersectVal` - The value of the node where the intersection occurs. This is `0` if there is no intersected node.
- `listA` - The first linked list.
- `listB` - The second linked list.
- `skipA` - The number of nodes to skip ahead in `listA` (starting from the head) to get to the intersected node.
- `skipB` - The number of nodes to skip ahead in `listB` (starting from the head) to get to the intersected node.
- The judge will then create the linked structure based on these inputs and pass the two heads, `headA` and `headB` to your program. If you correctly return the intersected node, then your solution will be accepted.

 
### Constraints:

- The number of nodes of `listA` is in the `m`.
- The number of nodes of `listB` is in the `n`.
- `1 <= m, n <= 3 * 104`
- `1 <= Node.val <= 105`
- `0 <= skipA < m`
- `0 <= skipB < n`
- `intersectVal` is `0` if `listA` and `listB` do not intersect.
- `intersectVal == listA[skipA] == listB[skipB]` if `listA` and `listB` intersect.
 

### Example :
![](ll2.png)
#### Input: 
```plaintext
intersectVal = 2, listA = [1,9,1,2,4], listB = [3,2,4], skipA = 3, skipB = 1
```
#### Output: 
```plaintext
Intersected at '2'
```
##### Explanation: 
- The intersected node's value is 2 (note that this must not be 0 if the two lists intersect).
- From the head of A, it reads as [1,9,1,2,4]. From the head of B, it reads as [3,2,4]. 
- There are 3 nodes before the intersected node in A; There are 1 node before the intersected node in B.
