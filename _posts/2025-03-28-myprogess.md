---
layout: post
title:  "Daily progess"
author: Charan 
categories: [ Daily progress ]
---


26-03-2025
tuf -  sortings/algorithms all 5 
Selection sort
Bubble sort
Insertion sort
Merge sort
Quick sort 
All basic algorithms have mostly no changes.

Arrays FAQ (medium,hard)
Two sum
 Given an array of integers nums and an integer target. Return the indices(0 - indexed) of two elements in nums such that they add up to target.
Each input will have exactly one solution, and the same element cannot be used twice. Return the answer in non-decreasing order.
  Using brute force two loops. o(n2)
  Using while loop (complex version of brute force) 0(n2)
  HashMap (target - sum) and then checking. 0()
3 sum 
  Given an integer array nums. Return all triplets such that:
i != j, i != k, and j != k
nums[i] + nums[j] + nums[k] == 0.
Notice that the solution set must not contain duplicate triplets. One  element can be a part of multiple triplets. The output and the triplets can be returned in any order.
Using brute force (3 loops stop when == 0)  0(n3)
Sorting and then using loops to get the sum using i,left,right; using while loop till left>right while checking for sum and going through it 

Sort an array of 0s 1s 2s
Given an array nums consisting of only 0, 1, or 2. Sort the array in non-decreasing order. The sorting must be done in-place, without making a copy of the original array.   
 Using Arrays.sort 0(n log n)
Something called Dutch National Flag Algorithm which is similar to quick sort  0(n)

Majority element-1
Given an integer array nums of size n, return the majority element of the array.
The majority element of an array is an element that appears more than n/2 times in the array. The array is guaranteed to have a majority element.
Using Hashmap 0(n).

Majority element-2
Given an integer array nums of size n. Return all elements which appear more than n/3 times in the array. The output can be returned in any order.
  Same as Majority element-1 but n/3 0(n).

LeetCode 
7. Reverse Integer
Usual method with some constraints 0(logn)
8. String to Integer (atoi)
 Conditions and checking them accordingly 0(n)

27-03-2025
LeetCode 
12. Integer to Roman
Giving the string values and dividing them till the end. 0(1)
15. 3Sum
Yesterday's 2nd one. same
16. 3Sum Closest
 Same as above but different conditions
18. 4Sum
Mentioned below


TUF 
Kadane's Algorithm
 Given an integer array nums, find the subarray with the largest sum and return the sum of the elements present in that subarray.
A subarray is a contiguous non-empty sequence of elements within an array
 Normal loop of max sum 0(n) 
4 sum
     Given an integer array nums and an integer target. Return all quadruplets [nums[a], nums[b], nums[c], nums[d]] such that:
·      a, b, c, d are all distinct valid indices of nums.
·      nums[a] + nums[b] + nums[c] + nums[d] == target.
Notice that the solution set must not contain duplicate quadruplets. One element can be a part of multiple quadruplets. The output and the quadruplets can be returned in any order.
 4 loops 0(n4)
Using similar procedure as 3 sum 0(n3)
Rotate Matrix by 90 deg
Given an N * N 2D integer matrix, rotate the matrix by 90 degrees clockwise.
The rotation must be done in place, meaning the input 2D matrix must be modified directly.
   1 Using double loop to copy and paste 0(n2)+0(n2)
Pascal's Triangle 1.
 Given two integers r and c, return the value at the rth row and cth column in a Pascal's Triangle.
        In Pascal's triangle:
The first row has one element with a value of 1.
Each row has one more element in it than its previous row.
The value of each element is equal to the sum of the elements directly above it when arranged in a triangle format.
Using the formula ncr= n!/r!*n-r!   0(c)
Pascal's Triangle 2
 Given an integer r, return all the values in the rth row in Pascal's Triangle in correct order.
In Pascal's triangle:
The first row has one element with a value of 1.
Each row has one more element in it than its previous row.
The value of each element is equal to the sum of the elements directly above it when arranged in a triangle format.
Using formula 0(r)
Pascal's Triangle 3
Given an integer n, return the first n rows of Pascal's triangle.
In Pascal's triangle:
The first row has one element with a value of 1.
Each row has one more element in it than its previous row.
The value of each element is equal to the sum of the elements directly above it when arranged in a triangle format.
 Same as pascal 2 just addition of list and recursion 0(n2)
  
   
28-03-2025

TUF
 leaders in the array.
  Given an integer array nums, return a list of all the leaders in the array.
A leader in an array is an element whose value is strictly greater than all elements to its right in the given array. The rightmost element is always a leader. The elements in the leader array must appear in the order they appear in the nums array.
  1 using reverse loop and checking for maximum 0(n)
Print the Matrix in spiral 
 Given an M * N matrix, print the elements in a clockwise spiral manner. Return an array with the elements in the order of their appearance when printed in a spiral manner.
                          1. Going through it as the perimeter from one end to another 0(m*n)
Find Missing Repeating Numbers
 Given an integer array nums of size n containing values from [1, n] and each value appears exactly once in the array, except for A, which appears twice and B which is missing.
Return the values A and B, as an array of size 2, where A appears in the 0-th index and B in the 1st index.
Using a hashset and formula 0(n) missing=expected sum−(actual sum−repeating number)
Count Inversions
Given an integer array nums. Return the number of inversions in the array.
Two elements a[i] and a[j] form an inversion if a[i] > a[j] and i < j.
It indicates how close an array is to being sorted.
A sorted array has an inversion count of 0.
An array sorted in descending order has maximum inversion.
Using brute force to check 0(n2)

29-03-2025

TUF 
Merge two sorted arrays without extra space
Given two integer arrays nums1 and nums2. Both arrays are sorted in non-decreasing order.
Merge both the arrays into a single array sorted in non-decreasing order.
The final sorted array should be stored inside the array nums1 and it should be done in-place.
nums1 has a length of m + n, where the first m elements denote the elements of nums1 and rest are 0s.
nums2 has a length of n.
Using loop to add in nums1 and and sort 0(n logn) 
Reverse Pairs
Given an integer array nums. Return the number of reverse pairs in the array.
An index pair (i, j) is called a reverse pair if:
0 <= i < j < nums.length
nums[i] > 2 * nums[j].
Double loops brute force 0(n2)
Leetcode
 19. Remove Nth Node From End of List
Brute force two different loops 0(2n)
One pass method 0(n)
24. Swap Nodes in Pairs
Normal two two swap 0(n)
29. Divide Two Integers
Normal division 0(1)
34. Find First and Last Position of Element in Sorted Array
For loop if target then update 0(n)
48. Rotate Image
Same as Rotate Matrix by 90 deg
50. Pow(x, n)
Func Math.pow 0(n)

30-03-2025
Tuf 
Maximum Product Subarray in an Array
Given an integer array nums. Find the subarray with the largest product, and return the product of the elements present in that subarray.
A subarray is a contiguous non-empty sequence of elements within an array.
Using a prefix and suffix to multiply 0(n)
Longest common prefix
Write a function to find the longest common prefix string amongst an array of strings.
If there is no common prefix, return an empty string ""
1. using loop to go through it after sorting 0(n log n)
Isomorphic string
Given two strings s and t, determine if they are isomorphic. Two strings s and t are isomorphic if the characters in s can be replaced to get t.
All occurrences of a character must be replaced with another character while preserving the order of characters. No two characters may map to the same character, but a character may map to itself.
While using ascii char 0(n)
Rotate string
Given two strings s and goal, return true if and only if s can become goal after some number of shifts on s.
A shift on s consists of moving the leftmost character of s to the rightmost position.
For example, if s = "abcde", then it will be "bcdea" after one shift.
return s.length() == goal.length() && (s + s).contains(goal); 0(n)
Using substring both to check 0(n2)
Valid Anagram
Given two strings s and t, return true if t is an anagram of s, and false otherwise.
An Anagram is a word or phrase formed by rearranging the letters of a different word or phrase, typically using all the original letters exactly once.
Convert to arrays and sort to equals 0(n logn)
Using array and a loop to add and sub each occurrence of a char 0(n)

Leetcode
53. Maximum Subarray
 Going through it and checking max 0(n)
54. Spiral Matrix
Already did the same thing in tuf
58. Length of Last Word
Splitting and finding the length0(n)

 31-03-2025
LeetCode
59. Spiral Matrix II
Same as spiral matrix but needs to generate the matrix 0(n2)
73. Set Matrix Zeroes
Going through the loop to find the zero and then again to equal the whole by using or 0(n2)+0(n2)
74. Search a 2D Matrix
 Normal search 0(n2)
Using the ascending order in a while loop while increasing slowly 0(m+n)
75. Sort Colors
Already did in tuf dutch national flag problem 0(n)
81. Search in Rotated Sorted Array II
Brute force 0(n)
82. Remove Duplicates from Sorted List II
Going through them 0(n)

 01-04-2025
LeetCode
88. Merge Sorted Array
Adding accordingly to the ascending order 0(m+n)
89. Gray Code
O(2^n) 
92. Reverse Linked List II
Swapping left and right 0(n)
94. Binary Tree Inorder Traversal
Recursive to find there values 0(n)
98. Validate Binary Search Tree
Recursive checking the nodes 0(n)
100. Same Tree
Recursive checking the nodes 0(n)
104. Maximum Depth of Binary Tree
Recursive checking the nodes separate left and right then using max func 0(n)
543. Diameter of Binary Tree
Similar to “104” but needs to check each and every node
938. Range Sum of BST
Same as “104”
22. Generate Parentheses
Recursive to generate

02-04-2025
LeetCode
111. Minimum Depth of Binary Tree
Similar to maximum 
112. Path Sum
Similar but need to minus it 






04-04-2025
Tuf 
Search X in sorted array
Given a sorted array of integers nums with 0-based indexing, find the index of a specified target integer. If the target is found in the array, return its index. If the target is not found, return -1.
Normal iterating 0(n)
Binary search 0(log n)
Lower Bound
Given a sorted array of nums and an integer x, write a program to find the lower bound of x. The lower bound algorithm finds the first or the smallest index in a sorted array where the value at that index is greater than or equal to a given key i.e. x.
If no such index is found, return the size of the array.
Normal iterating 0(n)
Binary search 0(log n)
Upper Bound
Given a sorted array of nums and an integer x, write a program to find the upper bound of x. The upper bound algorithm finds the first or the smallest index in a sorted array where the value at that index is greater than a given key i.e. x.
If no such index is found, return the size of the array.
Normal iterating 0(n)
Binary search 0(log n)
Search insert position
Given a sorted array nums and an integer x. Find the floor and ceil of x in nums. The floor of x is the largest element in the array which is smaller than or equal to x. The ceiling of x is the smallest element in the array greater than or equal to x. If no floor or ceil exists, output -1.
Normal iterating 0(n)
Binary search 0(log n)
Floor and Ceil in Sorted Array
Given a sorted array nums and an integer x. Find the floor and ceil of x in nums. The floor of x is the largest element in the array which is smaller than or equal to x. The ceiling of x is the smallest element in the array greater than or equal to x. If no floor or ceil exists, output -1.
Using lower and upper bound 0(log n)

First and last occurrence
Given an array of integers nums sorted in non-decreasing order, find the starting and ending position of a given target value. If the target is not found in the array, return [-1, -1].
Linear search 0(n)
Can also do two binary search
Search in rotated sorted array-I 
Search in rotated sorted array-II
Find minimum in Rotated Sorted Array

05-04-2025
Tuf 
Find out how many times the array is rotated
Single element in sorted array
Find square root of a number
Given a positive integer n. Find and return its square root. If n is not a perfect square, then return the floor value of sqrt(n).
(long) Math.floor(Math.sqrt(n)) 0(1)
06-04-2025
Leetcode 
118. Pascal's Triangle
Already did same one in tuf
119. Pascal's Triangle II
Similar sum





07-04-2025
Leetcode 
120. Triangle
Adding while checking the min of the array 0(n2)
125. Valid Palindrome
Normal string conv (not the best)
137. Single Number II
Bit manipulation using 2 0(n)
1768. Merge Strings Alternately
Using stringbuilder and iterating 0(n+m)
1071. Greatest Common Divisor of Strings
Recursion to check the size and do accordingly 0(n)


11-04-2025
Leetcode 
443. String Compression
Going through them and checking 0(n)
11. Container With Most Water
Going through them and checking for max and min of the borders 0(n)
643. Maximum Average Subarray I
Using a formula sum - 0(n)


Tuf 
Pow(x,n)
Implement the power function pow(x, n) , which calculates the x raised to n i.e. xn.
Generate Paranthesis
Power Set



24-04-2025
Tuf 
Find the smallest divisor 
 Koko eating bananas
Minimum days to make M bouquets
Aggressive cows

26-04-2025
Tuf
Book Allocation Problem
Find peak element
Median of 2 sorted arrays
Minimise max distance to gas stations
Kth element of 2 sorted arrays
Split array - largest sum
2D Arrays
Find row with maximum 1's
Search in a 2D matrix
Search in 2D matrix - II
Find Peak Element
Matrix Median


Leetcode 
4. Median of Two Sorted Arrays
774.Minimise max distance to gas stations
410. Split Array Largest Sum

27-04-2025
Tuf
Check if there exists a subsequence with sum K


29-04-2025
Tuf
Introduction to Singly LinkedList
Traversal in Linked List
Deletion in Linked List
Insertion in Linked List
Deletion of the head of LL
Deletion of the tail of LL
Deletion of the Kth element of LL
Delete the element with value X
Insertion at the head of LL
Insertion at the tail of LL
Insertion at the Kth position of LL
Insertion before the value X in LL


30-04-2025 & 01-05-2025
Tuf
Introduction to Doubly LL
Deletion in Doubly LL
Insertion in DLL
Convert Array to DLL
Delete head of DLL
Delete Tail of DLL
Delete Kth Element of DLL
Removing given node in DLL
Insert node before head in DLL
Insert node before tail in DLL
Insert node before (kth node) in DLL
Insert before given node in DLL


05-05-2025
Tuf
  Add two numbers in LL
Segregate odd and even nodes in LL
Sort a LL of 0's 1's and 2's
Remove Nth node from the back of the LL
Reverse a LL

06-05-2025
Tuf
Add one to a number represented by LL
Check if LL is palindrome or not
Find the intersection point of Y LL
Detect a loop in LL
Find the starting point in LL
Find Middle of Linked List
Length of loop in LL
Delete the middle node in LL
