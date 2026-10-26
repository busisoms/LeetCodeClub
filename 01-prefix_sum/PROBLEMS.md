# Prefix Sum: Problem List

## Goal

Learn how to use prefix sums to simplify calculations involving arrays and subarrays.

By the end of this topic, we should be able to:

- Build prefix sums from an array.
- Calculate range sums without repeatedly traversing an array.
- Recognise when a problem can be solved using cumulative sums.
- Use prefix sums with a hash map to count subarrays satisfying a condition.
- Handle variations involving negative numbers, parity, divisibility, and two-dimensional arrays.
- Explain the time and space trade-offs of each approach.

## How to Use This List

We divide the problems into two groups:

- **Individual Practice:** Learn the fundamentals and practise applying the technique independently.
- **Group Challenges:** Attempt each problem independently for approximately 30–45 minutes before discussing it with the club.

Follow the problem-solving process in the root `README.md`.

You do not need to memorise solutions. Focus on understanding what the prefix sum represents, why it helps, and how to derive the approach.

---

## 1. Individual Practice

Solve these problems independently before moving to the group challenges.

| # | Problem | Main Learning Objective | Difficulty |
|---|---|---|---|
| 1 | [Running Sum of 1d Array](https://leetcode.com/problems/running-sum-of-1d-array/) | Build a running total from left to right | Easy |
| 2 | [Range Sum Query - Immutable](https://leetcode.com/problems/range-sum-query-immutable/) | Precompute prefix sums to answer range queries efficiently | Easy |
| 3 | [Find Pivot Index](https://leetcode.com/problems/find-pivot-index/) | Compare left and right sums without repeatedly summing both sides | Easy |
| 4 | [Left and Right Sum Differences](https://leetcode.com/problems/left-and-right-sum-differences/) | Calculate left and right totals for every index | Easy |

### Before Moving On

You should be able to explain:

- What does `prefix[i]` represent?
- Why can a range sum be calculated by subtracting two prefix sums?
- Why does the formula sometimes use `prefix[left - 1]`?
- How can you calculate the right-side sum using the total sum?
- What is the difference between a prefix sum and a sliding window?
- When is preprocessing useful, especially if the same query must be answered repeatedly?

---

## 2. Group Challenges

Attempt each problem independently before discussing it with the club. Some of these combine prefix sums with hashing or other ideas, so focus on deriving the reasoning rather than immediately reaching for a formula.

### A. Prefix Sum + Hashing

| # | Problem | Main Learning Objective | Difficulty |
|---|---|---|---|
| 1 | [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Count subarrays using prefix sums and a frequency map | Medium |
| 2 | [Contiguous Array](https://leetcode.com/problems/contiguous-array/) | Transform a binary array into a running balance and find repeated balances | Medium |
| 3 | [Subarray Sums Divisible by K](https://leetcode.com/problems/subarray-sums-divisible-by-k/) | Use prefix-sum remainders to count divisible subarrays | Medium |
| 4 | [Continuous Subarray Sum](https://leetcode.com/problems/continuous-subarray-sum/) | Track remainders and earlier indices to satisfy subarray constraints | Medium |
| 5 | [Binary Subarrays With Sum](https://leetcode.com/problems/binary-subarrays-with-sum/) | Count subarrays with a target sum in a binary array | Medium |
| 6 | [Count Number of Nice Subarrays](https://leetcode.com/problems/count-number-of-nice-subarrays/) | Transform a condition about odd numbers into a subarray-sum problem | Medium |

### B. Prefix Sum Variations

| # | Problem | Main Learning Objective | Difficulty |
|---|---|---|---|
| 7 | [Number of Ways to Split Array](https://leetcode.com/problems/number-of-ways-to-split-array/) | Compare prefix and suffix sums at each valid split | Medium |
| 8 | [Range Sum Query 2D - Immutable](https://leetcode.com/problems/range-sum-query-2d-immutable/) | Extend prefix sums to two-dimensional arrays | Medium |
| 9 | [Matrix Block Sum](https://leetcode.com/problems/matrix-block-sum/) | Apply two-dimensional prefix sums to repeated rectangular queries | Medium |

### C. Capstone Challenge

| # | Problem | Main Learning Objective | Difficulty |
|---|---|---|---|
| 10 | [Number of Submatrices That Sum to Target](https://leetcode.com/problems/number-of-submatrices-that-sum-to-target/) | Combine two-dimensional prefix sums, subarray reasoning, and hashing | Hard |

Treat the capstone as a stretch goal. It is fine if the group needs to discuss the approach together after making an honest attempt.

---

## Group Discussion Checklist

For every challenge, discuss:

1. What does the prefix sum represent in this problem?
2. What information would repeated brute-force calculations require?
3. How does the prefix sum avoid repeating that work?
4. If a hash map is used, what does each key represent, and what does its value store?
5. Why must the map sometimes be initialised with a zero prefix sum?
6. How do negative numbers, repeated prefix sums, or remainder values affect the solution?
7. What are the time and space complexities?
8. Can the same reasoning solve a related problem with a different condition?

---

## Completion Criteria

Before considering this topic complete, each member should be able to:

- [ ] Build a prefix-sum array and explain what each entry means.
- [ ] Derive the formula for a range sum.
- [ ] Recognise when repeated range calculations make preprocessing worthwhile.
- [ ] Explain how equal prefix sums can identify subarrays with a target sum.
- [ ] Combine prefix sums with a hash map to count subarrays.
- [ ] Explain how prefix sums can be extended to two-dimensional arrays.
- [ ] Identify relevant edge cases, including zero, negative values, repeated sums, and boundary indices.
- [ ] Solve an unfamiliar problem by explaining why prefix sums are useful and how to apply them.

## Important Notes

- Solve and test problems on LeetCode before submitting solutions to the repository.
- Follow the branch and Pull Request workflow in the root `README.md`.
- Store solutions and learning notes in your own contributor folder.
- Do not memorise formulas without understanding what the prefix sums represent.
- A passing submission is a correctness checkpoint, not proof of optimality or understanding.

**The goal is to learn how cumulative information can turn repeated calculations into efficient solutions, and to recognise when that idea applies to a new problem.**