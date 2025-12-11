## Title
Rancher's Herd Selection

## Slug
ranchers-herd-selection

## Difficulty
Hard

## Description
A jagged cliff hosts n mineral veins running left to right.  
Each seam yields ore with grade ai.

A prospector must extract exactly m samples while moving strictly from the leftmost seam toward the right.  
When they reach any seam, they may either sample it or pass.  
However, the i-th sample they extract must have grade at least bi.

Before sampling, they may optionally inject a seam replica once:  
they may insert a single new seam of any integer grade k at any vertical position along the face  
(before the first seam, after the last seam, or between seams).

Your task is to determine the smallest integer k such that, after adding this replica seam,  
it becomes possible to extract m samples in valid order.  
If already possible without it, return 0.  
If no replica helps, return −1.
## Examples

### 1
#### Input
9 5  
3 5 2 3 3 5 8 1 2  
4 6 2 4 6

#### Output
6

### 2
#### Input
6 3  
1 2 6 8 2 1  
5 4 3

#### Output
3

## Input Format  
A line with integers n and m  
A line with n integers a1 … an representing beauty values  
A line with m integers b1 … bm representing required minimum beauty for each chosen flower

## Output Format
For every test case, Return the minimum integer k that guarantees a valid collection of m flowers.  
If no additional flower is needed, Return 0.  
If creating any flower cannot help, Return −1.

## Constraints  
1 ≤ m ≤ n ≤ 2×10⁵  
1 ≤ ai ≤ 10⁹  
1 ≤ bi ≤ 10⁹  
Sum of all n across test cases ≤ 2×10⁵

## Time Limit
2 seconds

## Memory Limit
256 megabytes

## Tags
dynamic-programming, hackwithinfy

## Company
infosys
