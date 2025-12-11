## Title
Orbital Debris Retrieval

## Slug
orbital-debris-retrieval

## Difficulty
Hard

## Description
A long courier route has n drop points arranged left to right, each with a package value ai.  
A rider must pick exactly m packages while proceeding strictly from the leftmost toward the right.  
When they reach a drop, they may either pick the package or move on.  
However, the i-th package they pick must have value at least bi.

Before starting, they may optionally place a decoy package once:  
they may add a single new package of any integer value k at any point on the route  
(before the first drop, after the last drop, or between drops).

Your task is to determine the smallest integer k such that, after adding this decoy,  
it becomes possible to pick m packages in valid order.  
If already possible without it, return 0.  
If no decoy helps, return −1.
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
