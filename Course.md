## Course Schedule

### Problem Statement:
There are a total of `numCourses` courses you have to take, labeled from `0` to `numCourses - 1`. You are given an array `prerequisites` where `prerequisites[i] = [ai, bi]` indicates that you must take course `bi` first if you want to take course `ai`.

For example, the pair `[0, 1]` indicates that to take course `0`, you have to first take course `1`.
Return `true` if you can finish all courses. Otherwise, return `false`.

### Constraints:
- `1 <= numCourses <= 2000`
- `0 <= prerequisites.length <= 5000`
- `prerequisites[i].length == 2`
- `0 <= ai, bi < numCourses`
- All the pairs `prerequisites[i]` are unique.

### Example:

**Input:**
```plaintext
numCourses = 2, prerequisites = [[1, 0]]
```
**Output:**
```plaintext
true
```
#### Explanation:
- There are a total of 2 courses to take. 
- To take course 1 you should have finished course 0. So it is possible.

