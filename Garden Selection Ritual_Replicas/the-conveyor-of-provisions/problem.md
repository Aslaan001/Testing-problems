## Title
The Conveyor of Provisions

## Slug
the-conveyor-of-provisions

## Difficulty
Hard

## Description
A long provisioning line carries n crates placed from left to right.  
Each crate has capacity ai.

A quartermaster must load exactly m crates while moving strictly from the left to the right.  
When they reach a crate, they may either load it or pass it.  
However, the i-th crate loaded must have capacity at least bi.

Before loading begins, they may optionally introduce one supply crate once:  
they may position a single new crate of any integer capacity k anywhere in the line  
(before the first crate, after the last crate, or between existing crates).

Your task is to determine the smallest integer k such that, after inserting this supply crate,  
it becomes possible to load m crates in the required order.  
If already possible with no new crate, return 0.  
If no supply crate can help, return −1.
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
