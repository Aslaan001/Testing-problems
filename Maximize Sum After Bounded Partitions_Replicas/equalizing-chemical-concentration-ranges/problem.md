## Title
Equalizing Chemical Concentration Ranges

## Slug
equalizing-chemical-concentration-ranges

## Difficulty
Medium

## Description
You are processing a sequence of values representing equalizing chemical concentration ranges. You may divide the array into contiguous segments of length at most k. Each segment is then replaced entirely by its maximum value. Your task is to determine the largest total sum achievable after such segmentation.



### 1

#### Input
7  
1 15 7 9 2 5 10  
3

#### Output
84

#### Explanation
One optimal partitioning transforms the array into:  
15 15 15 9 10 10 10

### 2

#### Input
11  
1 4 1 5 7 3 6 1 9 9 3  
4

#### Output
83

### 3

#### Input
1  
1  
1

#### Output
1

## Input Format

- The first line contains an integer n, the size of the array.  
- The second line contains n space-separated integers.  
- The third line contains the integer k.

## Output Format

Return a single integer — the maximum sum obtainable after partitioning.

## Constraints

1 ≤ n ≤ 500  
0 ≤ arr[i] ≤ 10^9  
1 ≤ k ≤ n

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
array, dynamic-programming

## Company
hackwithinfy
