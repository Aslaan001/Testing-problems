## Title
Orchard of Echoes

## Slug
orchard-of-echoes

## Difficulty
Hard

## Description
A long quilt show features n fabric swatches displayed left to right.  
Each swatch has thread count ai.

A quilter plans to pick exactly m swatches while moving strictly from the leftmost display toward the right.  
At each swatch they may either take it or pass.  
However, the i-th swatch they pick must have thread count at least bi.

Before shopping, they may optionally add a signature swatch once:  
they may insert a single new swatch with any integer thread count k at any position  
(before the first, after the last, or between swatches).

Your task is to determine the smallest integer k such that, after adding the signature swatch,  
it becomes possible to pick m swatches in valid order.  
If no signature is needed, return 0.  
If no signature helps, return −1.
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
