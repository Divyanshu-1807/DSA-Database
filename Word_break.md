## Word Break

### Problem Statement
Given a string `s` and a dictionary of strings `wordDict`, return **true** if `s` can be segmented into a space-separated sequence of one or more dictionary words.

**Note:** The same word in the dictionary may be reused multiple times in the segmentation.

### Constraints:

- `1 <= s.length <= 300`
- `1 <= wordDict.length <= 1000`
- `1 <= wordDict[i].length <= 20`
- `s` and `wordDict[i]` consist of only lowercase English letters.
- All the strings in `wordDict` are unique.

### Example:

**Input:**
```plaintext
s = "leetcode"
wordDict = ["leet", "code"]
```
**Output:**
```plaintext
true
```

**Explanation:** Return true because "leetcode" can be segmented as "leet code".
