## 3Sum

### Problem Statement
Given an integer array `nums`, return all the triplets `[nums[i], nums[j], nums[k]]` such that:
- `i != j`, `i != k`, and `j != k`
- `nums[i] + nums[j] + nums[k] == 0`

Notice that the solution set must **not contain duplicate triplets**.

### Constraints:
- `3 <= nums.length <= 3000`
- `-10^5 <= nums[i] <= 10^5`

### Example:
#### Input:
```bash
nums = [-1, 0, 1, 2, -1, -4]
```
#### Output:
```bash
[[-1,-1,2],[-1,0,1]]
```
### Explanation:
- nums[0] + nums[1] + nums[2] = (-1) + 0 + 1 = 0.
- nums[1] + nums[2] + nums[4] = 0 + 1 + (-1) = 0.
- nums[0] + nums[3] + nums[4] = (-1) + 2 + (-1) = 0.
- The distinct triplets are [-1,0,1] and [-1,-1,2].
- Notice that the order of the output and the order of the triplets does not matter.
