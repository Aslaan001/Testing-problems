## Title
Stargazer's Satellite Salvage

## Slug
stargazers-satellite-salvage

## Difficulty
Hard

## Description
A long fairground path features n token booths arranged left to right.  
Each booth offers a token worth ai.

A child wants to collect exactly m tokens while walking strictly from the leftmost booth toward the right.  
When they reach a booth, they may either collect the token or skip it.  
However, the i-th token they collect must be worth at least bi.

Before visiting, they may optionally craft one special token once:  
they may insert a single new token of any integer worth k into the path  
(before the first booth, after the last booth, or between booths).

Your task is to determine the smallest integer k such that, after inserting this special token,  
it becomes possible to collect m tokens in valid order.  
If no insertion is needed, return 0.  
If no token value helps, return −1.
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
