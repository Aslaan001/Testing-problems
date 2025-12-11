## Title
Island Forager's Quest

## Slug
island-foragers-quest

## Difficulty
Hard

## Description
A small island shoreline hosts n foraged goods lined left to right.  
Each find has freshness ai.

A forager wishes to collect exactly m goods while walking strictly from the leftmost cove toward the right.  
When they encounter an item, they may either pick it or ignore it.  
However, the i-th item they pick must have freshness at least bi.

Before the foraging trip, they may optionally plant a replacement once:  
they may add a single new good of any integer freshness k at any position on the shore  
(before the first item, after the last item, or between items).

Your task is to determine the smallest integer k such that, after placing this replacement,  
it becomes possible to collect m goods in valid order.  
If already possible with no replacement, return 0.  
If no placement can help, return −1.
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
