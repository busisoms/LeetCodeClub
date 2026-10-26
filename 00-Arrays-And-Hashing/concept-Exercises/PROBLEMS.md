# Arrays and Hashing: Problem List

## Goal

Build a strong foundation in arrays and hash-based data structures, including:

- Traversing and analysing arrays.
- Using `HashSet` and `HashMap` to store and look up information efficiently.
- Counting frequencies and detecting duplicates.
- Recognising when hashing can replace repeated searching.
- Choosing an appropriate data structure for a problem.
- Analysing time and space complexity.

We are aiming to understand the reasoning behind these techniques and apply them to unfamiliar problems.

## How to Use This List

We divide the problems into two groups:

- **Individual Practice:** Solve these independently to build familiarity with the fundamentals.
- **Group Challenges:** Attempt these independently before discussing your approach with the club.

Follow the problem-solving process in the root `README.md`.

For every problem, try to explain why your approach works, not just why LeetCode accepts it.

---

## 1. Individual Practice

Solve these problems independently. Focus on understanding the problem, deriving an approach, and implementing it correctly in Java.

| # | Problem | Main Learning Objective | Difficulty |
|---|---|---|---|
| 1 | [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/) | Detect duplicates using a `HashSet` | Easy |
| 2 | [Valid Anagram](https://leetcode.com/problems/valid-anagram/) | Compare character frequencies | Easy |
| 3 | [Two Sum](https://leetcode.com/problems/two-sum/) | Use a `HashMap` to find complements | Easy |
| 4 | [Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/) | Use sets to identify common elements | Easy |
| 5 | [Majority Element](https://leetcode.com/problems/majority-element/) | Count frequencies using a map | Easy |
| 6 | [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/) | Count frequencies and preserve the required order | Easy |

### Before Moving On

You should be able to explain:

- When would you use a `HashSet` instead of a `HashMap`?
- How can a hash-based structure reduce repeated searching?
- When is an array sufficient for counting frequencies?
- What are the average time complexities of common `HashSet` and `HashMap` operations?
- What extra memory does your solution use?

---

## 2. Group Challenges

Attempt each problem independently for approximately 30–45 minutes before the group discussion. If you're stuck, record what you tried and the point where your reasoning broke down.

| # | Problem | Main Learning Objective | Difficulty |
|---|---|---|---|
| 1 | [Group Anagrams](https://leetcode.com/problems/group-anagrams/) | Design a key that groups equivalent strings | Medium |
| 2 | [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/) | Combine frequency counting with selecting the most frequent elements | Medium |
| 3 | [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/) | Use a set to avoid repeated work | Medium |
| 4 | [Valid Sudoku](https://leetcode.com/problems/valid-sudoku/) | Track duplicates across rows, columns, and boxes | Medium |
| 5 | [4Sum II](https://leetcode.com/problems/4sum-ii/) | Use a map of pair sums to reduce nested-loop work | Medium |
| 6 | [Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency/) | Combine frequency counting with ordering | Medium |
| 7 | [Find and Replace Pattern](https://leetcode.com/problems/find-and-replace-pattern/) | Track consistent character mappings | Medium |
| 8 | [Insert Delete GetRandom O(1)](https://leetcode.com/problems/insert-delete-getrandom-o1/) | Combine a hash map and an array-backed list | Medium |
| 9 | [Bulls and Cows](https://leetcode.com/problems/bulls-and-cows/) | Count unmatched digits and handle repeated values correctly | Medium |

### Group Discussion Checklist

For each problem, discuss:

1. What was the key observation that led to the solution?
2. What was your first approach, and why did you change it?
3. Why is the chosen data structure appropriate?
4. What edge cases did you consider?
5. What are the time and space complexities?
6. Could the same reasoning help solve another problem?

---

## 3. Optional Stretch Challenge

For anyone who wants to go deeper:

| Problem | Main Learning Objective | Difficulty |
|---|---|---|
| [Design HashMap](https://leetcode.com/problems/design-hashmap/) | Understand how a hash map can be implemented from scratch | Easy |

Try this after gaining experience with Java's built-in `HashMap`. The goal is to understand the underlying design, not simply to use the library.

---

## Completion Criteria

Before considering this topic complete, each member should be able to:

- [ ] Recognise when a set or map may be useful.
- [ ] Use frequency counting to solve problems involving duplicates or repeated values.
- [ ] Use a map to connect values with useful information, such as indices or counts.
- [ ] Explain how a carefully chosen key can group related items.
- [ ] Identify when hashing avoids unnecessary repeated work.
- [ ] Explain the time and space trade-offs of their solutions.
- [ ] Solve at least one unfamiliar problem using the ideas learned here.

## Important Notes

- Solve and test each problem on LeetCode before submitting your solution to the repository.
- Follow the branch and Pull Request workflow in the root `README.md`.
- Store your solution and learning notes in your own contributor folder.
- Do not copy a solution simply because it passes. Make sure you can explain how it works.
- We value the reasoning behind a solution more than the number of problems completed.

**The goal is to learn when and why to use arrays, sets, and maps, and to recognise those opportunities in new problems.**