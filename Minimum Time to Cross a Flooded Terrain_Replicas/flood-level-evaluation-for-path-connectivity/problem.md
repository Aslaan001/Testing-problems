## Title
Flood Level Evaluation for Path Connectivity

## Slug
flood-level-evaluation-for-path-connectivity

## Difficulty  
Hard  

## Description

In a emergency navigation simulation, a square terrain is modeled as a grid where each cell represents a specific elevation above sea level.

As environmental conditions worsen, water levels increase uniformly over time. At any given time value, locations with elevation less than or equal to the current water level are submerged and can be traversed, while higher elevation cells remain inaccessible.

A response unit begins at the top left position of the grid and must reach the bottom right position. Movement is restricted to adjacent cells in the four primary directions, and transitions are allowed only when both the current and target cells are submerged at the same time level.

The challenge is to determine the minimum time at which a continuous path becomes available from the starting position to the destination. This time represents the earliest moment when rising water levels enable full connectivity across the required terrain.

The solution must correctly account for unique elevation values and efficiently evaluate reachability as water levels increase.
## Examples  

### 1  

#### Input  
2  
0 2  
1 3  

#### Output  
3  

#### Explanation  

At time 0, only the starting cell is accessible.  
Movement becomes possible only when the water level reaches 3, at which point all required cells are flooded and connected.

### 2  

#### Input  
5  
0 1 2 3 4  
24 23 22 21 5  
12 13 14 15 16  
11 17 18 19 20  
10 9 8 7 6  

#### Output  
16  

#### Explanation  

The team must wait until the water level reaches 16 so that a continuous path exists from the start to the destination.

## Input Format  

- The first line contains an integer n — the size of the grid  
- The next n lines each contain n space-separated integers representing the elevation grid  

## Output Format  

Return a single integer representing the minimum time required to reach the bottom-right cell.

## Constraints  

1 ≤ n ≤ 50  
0 ≤ grid[i][j] < n²  
Each elevation value is unique  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

queue.