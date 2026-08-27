# Problem: Coin change — minimum coins to make amount N.

**Category:** Dynamic Programming  
**Date:** 2026-08-27

## Problem Statement

Coin change — minimum coins to make amount N.

## Approach

DP table where dp[i] = min coins for amount i. Transition: dp[i] = min(dp[i], dp[i-coin]+1).

## Complexity

- Time: O(n log n) in the general case
- Space: O(n) auxiliary

## Key Insight

Breaking the problem into smaller subproblems and recognising the pattern
is more valuable than memorising the solution.

---
*Entry #239 in this journal.*
