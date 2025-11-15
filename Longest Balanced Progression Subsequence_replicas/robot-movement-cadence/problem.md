## Title  
Robot Movement Cadence

## Slug  
robot-movement-cadence

## Difficulty  
Medium

## Description  

A robot logs its forward displacement measurements. A subsequence forms a proper cadence if each movement differs from the last by a constant value. Compute the longest cadence subsequence.

## Examples  

### 1  

#### Input  
4  
3 6 9 12

#### Output  
4

#### Explanation  
The entire array forms a balanced progression with difference 3.

### 2  

#### Input  
5  
9 4 7 2 10

#### Output  
3

#### Explanation  
A longest balanced subsequence is [4, 7, 10].

### 3  

#### Input  
7  
20 1 15 3 10 5 8

#### Output  
4

#### Explanation  
A valid longest balanced subsequence is [20, 15, 10, 5].

## Input Format  

- The first line contains an integer n.  
- The second line contains n integers representing the array nums.

## Output Format  

Return a single integer: the length of the longest balanced progression subsequence.

## Constraints  

2 ≤ n ≤ 1000  
0 ≤ nums[i] ≤ 500  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

dynamic programming.
