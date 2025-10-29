## Title

First Tower Leader

## Slug

first-tower-leader

## Difficulty

Medium

## Description

In a city skyline, each building's height is given in an array.  
You must find the first tower that is taller than the combined height of all buildings before and after it.

Formally, find the smallest index i such that:

- The sum of all previous heights is less than height[i].  
- The sum of all heights after i is also less than height[i].

If no such tower exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
At index 1:
Left sum = 1  
Right sum = 3  
Both are less than 5 → output 1.

### 2

#### Input
5
2 3 4 1 2

#### Output
-1

#### Explanation
No tower meets the requirement.

## Input Format
- First line: integer n — number of buildings.  
- Second line: n integers — heights of buildings.

## Output Format
- One integer — the first leader tower index or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
