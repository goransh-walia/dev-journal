# Problem: Find the first occurrence of a target in a sorted array.

**Category:** Binary Search  
**Date:** 2026-08-07

## Problem Statement

Find the first occurrence of a target in a sorted array.

## Approach

Binary search but continue left even after finding the target. Track `result = mid` when found.

## Complexity

- Time: O(n log n) in the general case
- Space: O(n) auxiliary

## Key Insight

Breaking the problem into smaller subproblems and recognising the pattern
is more valuable than memorising the solution.

---
*Entry #219 in this journal.*
