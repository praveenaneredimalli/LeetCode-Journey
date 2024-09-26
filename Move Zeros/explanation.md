# Problem Name: Move Zeroes

## Problem Description:
Given an integer array `nums`, move all 0's to the end of the array while maintaining the relative order of the non-zero elements. You must do this in-place without making a copy of the array.

## Approach:
1. Initialize a pointer `j` to track the position for the next non-zero element.
2. Loop through the array using pointer `i`:
   - If the current element is non-zero, assign it to the `j`-th position and increment `j`.
3. After processing all elements, fill the remaining positions from `j` to the end of the array with 0s.

This ensures all non-zero elements remain in their original order, and all 0s are moved to the end of the array.

## Time Complexity:
Time complexity is O(n), where `n` is the number of elements in the array. The array is traversed twice, but each element is handled only once.

## Space Complexity:
Space complexity is O(1), as the operation is performed in-place without using extra space.

## Problem Link:
[Move Zeroes](https://leetcode.com/problems/move-zeroes/)
