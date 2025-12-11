## Title
Subway Hopper's Stops

## Slug
subway-hoppers-stops

## Difficulty
Hard

## Description
A long workshop bench contains n tools placed left to right.  
Each tool has a utility ai.

A craftsman must select exactly m tools while moving strictly from the left toward the right.  
At each tool they may either pick it or skip it.  
However, the i-th tool they pick must have utility at least bi.

Before starting, they may optionally add a prototype tool once:  
they may insert a single new tool with any integer utility k at any position  
(before the first, after the last, or between tools).

Your task is to determine the smallest integer k such that, after adding this prototype,  
it becomes possible to pick m tools in valid order.  
If already possible without it, return 0.  
If no prototype helps, return −1.
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
