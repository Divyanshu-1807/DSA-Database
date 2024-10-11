## Minimum Moves to Reach Target Score

### Problem Statement:
You are playing a game with integers. You start with the integer `1` and you want to reach the integer `target`.

In one move, you can either:

- Increment the current integer by one (i.e., `x = x + 1`).
- Double the current integer (i.e., `x = 2 * x`).

You can use the increment operation any number of times; however, you can only use the double operation at most `maxDoubles` times.

Given the two integers `target` and `maxDoubles`, return the minimum number of moves needed to reach `target` starting with `1`.

## Constraints:

- `1 <= target <= 109`
- `0 <= maxDoubles <= 100`

## Example:

**Input:** 
```plaintext
target = 5, maxDoubles = 0
```
**Output:** 
```plaintext
4
```
**Explanation:** Keep incrementing by 1 until you reach target.
