## Title
Twilight Bloom Cutting Challenge

## Slug
twilight-bloom-cutting-challenge

## Difficulty
Hard

## Description
Twilight Bloom Cutting Challenge takes place in a circular region of radius r centered at the origin.

Inside this domain lie n important points, each strictly within the circle at coordinates (xi, yi).  
No two points coincide, and each lies at most 0.9r from the center.

A straight-line cut may be applied to divide the circular region.  
All points must lie strictly on the same side of the cutting line, though any on the line may be assigned freely.

Among all valid cuts, your task is to determine the maximum achievable area of the smaller resulting region while ensuring every point remains on a single side of the cut.

## Examples

### Example 1
#### Input

4 5
-3 -3
3 -3
-3 3
3 3
#### Output
11.182380450040

### 2
#### Input
7 15
9 -4
2 -2
8 3
0 4
-6 10
6 6
3 5

#### Output
353.429173528852



## Input Format
A line containing two integers n and r  
n is the number of strawberries  
r is the radius of the cake

The next n lines each contain two integers xi, yi representing strawberry coordinates.

## Output Format
Return a single real number: the maximum possible area of the smaller piece of cake when the cut ensures all strawberries lie on the same side of the line.

## Constraints
1 ≤ n ≤ 2 × 10⁵  
1 ≤ r ≤ 10⁶  
sqrt(xi² + yi²) ≤ 0.9r  
All strawberry positions are distinct

## Time Limit
1 second

## Memory Limit
256 megabytes

## Tags
geometry, hackwithinfy.

## Company
infosys
