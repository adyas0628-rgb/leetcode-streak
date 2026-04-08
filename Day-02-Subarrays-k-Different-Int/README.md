# Count the number of subarrays with k distinct integers

## Approach

Same as the previous one, count number of subarrays with number of different integers <=k and subtract count number of subarrays with number of different integers <=k-1 from it

## Why?

Because if we directly count number of subarrays with number of different integers ==k, we cannot be sure when to shrink or expand our window

## Complexity

Time: O(2n*2)
Space: O(n)  -> for map
