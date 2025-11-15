## Title  
Strict Elevation Run

## Slug  
strict-elevation-run

## Difficulty  
Easy  

## Description  

You are given an unsorted array of integers `nums`. Imagine these values represent sequential readings from machine vibration levels. Your task is to determine the length of the `longest continuous increasing streak` within these measurements.

A continuous increasing streak is a subarray `nums[l...r]` such that `l < r` and for every index `l <= i < r`, the condition `nums[i] < nums[i + 1]` holds.

Return the length of the longest stretch where the readings are strictly increasing.

## Examples  

### 1  

#### Input  
5
1 3 5 4 7 

#### Output  
3  

#### Explanation  
The longest continuous increasing streak is `[1, 3, 5]` with length 3.  
Even though `[1, 3, 5, 7]` is an increasing streak, it is not continuous as elements 5 and 7 are separated by 4.  

### 2  

#### Input  
5
2 2 2 2 2

#### Output  
1  

#### Explanation  
The longest continuous increasing streak is `[2]` with length 1. Note that it must be strictly increasing, so all elements must be distinct.  

## Input Format  

- First line contains an integer `n` — the number of elements in the array.  
- Second line contains `n` space-separated integers representing `nums`.  

## Output Format  

Retrun a single integer — the length of the longest continuous increasing streak in the array.  

## Constraints  

1 ≤ n ≤ 10⁴  
-10⁹ ≤ nums[i] ≤ 10⁹  

## Time Limit  
1 second  

## Memory Limit  
512 MB  

## Tags  
arrays, sliding-window, dynamic-programming  
