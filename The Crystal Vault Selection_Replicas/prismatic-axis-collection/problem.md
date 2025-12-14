## Title
Prismatic Axis Collection

## Slug
prismatic-axis-collection

## Difficulty
Hard

## Description
In a scenario known as prismatic axis collection, an explorer enters a perfectly structured cubic chamber composed of layered grids.
The chamber consists of n layers, each containing an n by n arrangement of values, forming a complete cube of size n.

The explorer must select exactly n cells while minimizing the total collected value.
Each cell is identified by a triple of coordinates, and strict stability constraints apply.

No two chosen cells may share the same position along any of the three axes.
That is, all selected cells must have distinct coordinates in every dimension.

Determine the minimum possible sum achievable under these conditions.

## Examples

### 1
#### Input
3  
1 2 3  
4 5 6  
7 8 9  
1 1 1  
2 2 2  
3 3 3  
4 3 0  
2 1 4  
9 8 9  

#### Output
5

## Input Format
- The first line contains a single integer n.  
- The next n² lines each contain n integers.  

The values are given layer by layer.  
For coordinates (x, y, z), the value at that position is the z-th number in the ((x−1) × n + y)-th line.

## Output Format
Return a single integer — the minimum possible sum of the selected crystals.

## Constraints
2 ≤ n ≤ 12  
0 ≤ value ≤ 2 × 10⁷  

## Time Limit
3 seconds

## Memory Limit
1024 megabytes

## Tags
recursion, hackwithinfy

## Company
infosys
