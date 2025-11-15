## Title  
Alien Planet Terrain Challenge

## Slug  
alien-planet-terrain-challenge

## Difficulty  
Medium

## Description  

An astronaut navigates alien terrain that alters shield energy. Shield energy must stay positive. Find starting shield level.

## Examples  

### 1  

#### Input  
3 3  
-2 -3 3  
-5 -10 1  
10 30 -5

#### Output  
7

#### Explanation  
If the traveler starts with 7 stamina and follows a safe path, stamina never drops to zero or below.

### 2  

#### Input  
1 1  
0

#### Output  
1

#### Explanation  
Even without hazards, the traveler must begin with at least 1 stamina.

## Input Format  

- The first line contains two integers m and n.  
- Each of the next m lines contains n integers representing the grid.

## Output Format  

Return a single integer: the minimum initial stamina required.

## Constraints  

1 ≤ m, n ≤ 200  
-1000 ≤ grid[i][j] ≤ 1000  

## Time Limit  
1 second  

## Memory Limit  
512 MB  

## Tags  
dynamic programming, grid traversal
