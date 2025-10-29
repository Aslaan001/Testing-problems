## Title

First Champion Level

## Slug

first-champion-level

## Difficulty

Medium

## Description

In a video game, each level has a difficulty score represented as an array.  
Your task is to find the first level that stands above the rest —  
the one whose difficulty is greater than the sum of all difficulties before and after it.

Find the smallest index i such that:

- Sum of previous levels < arr[i]  
- Sum of later levels < arr[i]

If no such level exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Level 1 dominates with difficulty 5.

### 2

#### Input
5
2 2 3 4 1

#### Output
-1

#### Explanation
No level dominates both sides.

## Input Format
- First line: integer n — number of levels.  
- Second line: n integers — level difficulties.

## Output Format
- One integer — the first champion level index or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
