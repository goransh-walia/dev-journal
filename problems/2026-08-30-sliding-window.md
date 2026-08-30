# Problem: Find the longest substring without repeating characters.

**Category:** Sliding Window  
**Date:** 2026-08-30

## Problem Statement

Find the longest substring without repeating characters.

## Approach

Use a set and two pointers. Expand right pointer, shrink left when a duplicate is found. O(n) time.

## Complexity

- Time: O(n log n) in the general case
- Space: O(n) auxiliary

## Key Insight

Breaking the problem into smaller subproblems and recognising the pattern
is more valuable than memorising the solution.

---
*Entry #242 in this journal.*
