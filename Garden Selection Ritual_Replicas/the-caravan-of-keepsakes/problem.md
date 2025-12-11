## Title
The Caravan of Keepsakes

## Slug
the-caravan-of-keepsakes

## Difficulty
Hard

## Description
A long row of curiosities travels in a caravan of keepsakes laid left to right.  
Each keepsake has charm ai.

A buyer plans to acquire exactly m keepsakes while proceeding strictly from the left caravan toward the right.  
When they pass any item, they may either acquire it or pass it by.  
However, the i-th keepsake they acquire must have charm at least bi.

Before the journey, they may optionally add a gifted keepsake once:  
they may place one new keepsake of any integer charm k anywhere in the caravan  
(before the first, after the last, or between keepsakes).

Your task is to determine the smallest integer k such that, after adding this gift,  
it becomes possible to acquire m keepsakes in sequence.  
If already possible with no gift, return 0.  
If no gift value helps, return −1.
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
