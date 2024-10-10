## Trapping Rain Water

### Problem Statement

Given `n` non-negative integers representing an elevation map where the width of each bar is 1, compute how much water can be trapped after raining.

### Constraints
- `n == height.length`
- `1 <= n <= 2 * 10^4`
- `0 <= height[i] <= 10^5`

### Example
![](rainwater.png)

**Input:** 
```bash
height = [0,1,0,2,1,0,1,3,2,1,2,1]
```
**Output:** 
```bash
6
```
**Explanation:** The above elevation map (black section) is represented by array [0,1,0,2,1,0,1,3,2,1,2,1]. In this case, 6 units of rain water (blue section) are being trapped.
