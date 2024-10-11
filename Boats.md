## Boats to Save People

### Problem Statement:
You are given an array `people` where `people[i]` is the weight of the ith person, and an infinite number of boats where each boat can carry a maximum weight of `limit`. Each boat can carry at most two people at the same time, provided the sum of the weight of those people does not exceed the `limit`.

Return the minimum number of boats required to carry every given person.

### Constraints:
- `1 <= people.length <= 5 * 104`
- `1 <= people[i] <= limit <= 3 * 104`

### Example:
**Input:**  
```plaintext
people = [1, 2], limit = 3
```
**Output:**  
```plaintext
1
```
**Explanation:**  1 boat can carry both people (1, 2).
