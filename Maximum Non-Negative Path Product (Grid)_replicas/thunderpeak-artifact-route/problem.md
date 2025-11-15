## Title  
Thunderpeak Artifact Route

## Slug  
thunderpeak-artifact-route

## Difficulty  
Medium

## Description  

You are given a 2D grid of integers representing environmental stability values across the terrain.  

You start at the top-left cell and must reach the bottom-right cell, moving only right or down.  

The value of a path is defined as the product of all numbers along it. Your goal is to determine the `maximum non-negative path product`.  

Return the result modulo 1000000007. If every possible path yields a negative product, return -1.
## Examples  

### 1  

#### Input  
3 3  
-1 -2 -3  
-2 -3 -3  
-3 -3 -2

#### Output  
-1

#### Explanation  
Every possible path from start to end results in a negative product, so the answer is -1.


### 2  

#### Input  
3 3  
1 -2 1  
1 -2 1  
3 -4 1

#### Output  
8

#### Explanation  
One optimal path is  
1 → 1 → -2 → -4 → 1  
Product = 1 * 1 * -2 * -4 * 1 = 8.  
![alt text](image.png)

## Input Format  

- The first line contains two integers m and n.  
- Each of the next m lines contains n integers representing the grid.

## Output Format  

Return a single integer: the maximum non-negative path product modulo 1000000007, or -1 if no valid non-negative path exists.

## Constraints  

1 ≤ m, n ≤ 15  
-4 ≤ grid[i][j] ≤ 4  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

dynamic programming.