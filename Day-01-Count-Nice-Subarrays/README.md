# Count Number of Nice Subarrays

## Problem
Given an array, count subarrays with exactly k odd numbers

## Approach
Used sliding window and two pointer technique

## New
Consider all odd numbers-> 1 and all even numbers-> 0
Ans = (Number of subarrays with sum<=k) - (Number of subarrays with sum<= k-1)

## Complexity
Time: O(2n *2)
Space: O(1)
