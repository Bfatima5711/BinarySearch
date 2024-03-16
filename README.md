# BinarySearch
Binary Search

//Easy level : question 1

Problem Statement: Binary Search

Given:
Given an array of integers nums which is sorted in ascending order, and an integer target, write a function to search target in nums. If target exists, then return its index. Otherwise, return -1.
You must write an algorithm with O(log n) runtime complexity.

Example 1:
Input: nums = [-1,0,3,5,9,12], target = 9
Output: 4
Explanation: 9 exists in nums and its index is 4

Constraints:
1 <= nums.length <= 104
-104 < nums[i], target < 104
All the integers in nums are unique.
nums is sorted in ascending order.

Problem Link: https://leetcode.com/problems/binary-search/description/

Note: for code check attached file with name Binary Search

//Easy level : question 2

Problem Statement: Search Insert Position

Given:
Given a sorted array of distinct integers and a target value, return the index if the target is found. If not, return the index where it would be if it were inserted in order.
You must write an algorithm with O(log n) runtime complexity.

Example 1:
Input: nums = [1,3,5,6], target = 5
Output: 2

Example 2:
Input: nums = [1,3,5,6], target = 2
Output: 1

Constraints:
1 <= nums.length <= 104
-104 <= nums[i] <= 104
nums contains distinct values sorted in ascending order.
-104 <= target <= 104

Problem Link: https://leetcode.com/problems/search-insert-position/description/

Note: for code check attached file with name Search Insert Position


//Medium level : question 1

Problem Statement: Find First and Last Position of Element in Sorted Array

Given:
Given an array of integers nums sorted in non-decreasing order, find the starting and ending position of a given target value.
If target is not found in the array, return [-1, -1].
You must write an algorithm with O(log n) runtime complexity.

Example 1:
Input: nums = [5,7,7,8,8,10], target = 8
Output: [3,4]

Example 2:
Input: nums = [5,7,7,8,8,10], target = 6
Output: [-1,-1]

Example 3:
Input: nums = [], target = 0
Output: [-1,-1]
 
Constraints:
0 <= nums.length <= 105
-109 <= nums[i] <= 109
nums is a non-decreasing array.
-109 <= target <= 109

Problem Link: https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/description/

Note: for code check attached file with name Find First and Last Position of Element in Sorted Array

//Medium level : question 2

Problem Statement: Search in Rotated Sorted Array

Given:
There is an integer array nums sorted in ascending order (with distinct values).
Prior to being passed to your function, nums is possibly rotated at an unknown pivot index k (1 <= k < nums.length) such that the resulting array is [nums[k], nums[k+1], ..., nums[n-1], nums[0], nums[1], ..., nums[k-1]] (0-indexed). For example, [0,1,2,4,5,6,7] might be rotated at pivot index 3 and become [4,5,6,7,0,1,2].
Given the array nums after the possible rotation and an integer target, return the index of target if it is in nums, or -1 if it is not in nums.
You must write an algorithm with O(log n) runtime complexity.

Example 1:
Input: nums = [4,5,6,7,0,1,2], target = 0
Output: 4

Example 2:
Input: nums = [4,5,6,7,0,1,2], target = 3
Output: -1

Example 3:
Input: nums = [1], target = 0
Output: -1

Constraints:
1 <= nums.length <= 5000
-104 <= nums[i] <= 104
All values of nums are unique.
nums is an ascending array that is possibly rotated.
-104 <= target <= 104

Problem Link: https://leetcode.com/problems/search-in-rotated-sorted-array/description/

Note: for code check attached file with name Search in Rotated Sorted Array

//Medium level : question 3

Problem Statement: Single Element in a Sorted Array

Given:
You are given a sorted array consisting of only integers where every element appears exactly twice, except for one element which appears exactly once.
Return the single element that appears only once.
Your solution must run in O(log n) time and O(1) space.

Example 1:
Input: nums = [1,1,2,3,3,4,4,8,8]
Output: 2

Example 2:
Input: nums = [3,3,7,7,10,11,11]
Output: 10
 
Constraints:
1 <= nums.length <= 105
0 <= nums[i] <= 105

Problem Link: https://leetcode.com/problems/single-element-in-a-sorted-array/

Note: for code check attached file with name Single Element in a Sorted Array
