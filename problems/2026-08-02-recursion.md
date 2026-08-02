# Problem: Generate all subsets of a set.

**Category:** Recursion  
**Date:** 2026-08-02

## Problem Statement

Generate all subsets of a set.

## Approach

For each element, recurse with it included and excluded. 2^n subsets total.

## Complexity

- Time: O(n log n) in the general case
- Space: O(n) auxiliary

## Key Insight

Breaking the problem into smaller subproblems and recognising the pattern
is more valuable than memorising the solution.

---
*Entry #214 in this journal.*
