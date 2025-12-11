## Title
Mariner's Net Collection

## Slug
mariners-net-collection

## Difficulty
Hard

## Description
A long net trawl collects n fish drifting left to right, each with size ai.  
A fisher wants to keep exactly m fish while moving strictly from the left toward the right.  
Upon encountering a fish, they may keep it or let it go.  
However, the i-th fish they keep must have size at least bi.

Before setting the net, they may optionally release a single bait fish once:  
they may introduce one new fish of any integer size k at any place in the line  
(before the first fish, after the last fish, or between existing fish).

Your task is to determine the smallest integer k such that, after releasing this fish,  
it becomes possible to keep m fish in valid order.  
If already possible with no release, return 0.  
If no released fish value helps, return −1.
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
