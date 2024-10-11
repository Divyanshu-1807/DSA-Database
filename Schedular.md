## Task Scheduler

### Problem Statement:
You are given an array of CPU tasks, each labeled with a letter from A to Z, and a number `n`. Each CPU interval can be idle or allow the completion of one task. Tasks can be completed in any order, but there is a constraint: there must be a gap of at least `n` intervals between two tasks with the same label.

Return the **minimum number of CPU intervals** required to complete all tasks.

### Constraints:
- `1 <= tasks.length <= 10^4`
- `tasks[i]` is an uppercase English letter.
- `0 <= n <= 100`

### Example:

#### Input:
```plaintext
tasks = ["A","A","A","B","B","B"], n = 2
```
#### Output:
```plaintext
8
```
#### Explanation:
A possible sequence is: A -> B -> idle -> A -> B -> idle -> A -> B.

After completing task A, you must wait two intervals before doing A again.
The same applies to task B. In the 3rd interval, neither A nor B can be done, so you idle. 
By the 4th interval, you can do A again as 2 intervals have passed.
