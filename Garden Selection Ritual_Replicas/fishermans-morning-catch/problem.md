## Title
Fisherman's Morning Catch

## Slug
fishermans-morning-catch

## Difficulty
Hard

## Description
A long field of driftwood lines the riverbank with n logs from left to right.  
Each log has durability ai.

A builder seeks to salvage exactly m logs while walking strictly from the left bank toward the right.  
When they reach a log, they may either take it or pass it by.  
However, the i-th log they take must have durability at least bi.

Before beginning, they may optionally anchor a sample log once:  
they may place a single new log with any integer durability k at any position  
(before the first, after the last, or between logs).

Your task is to determine the smallest integer k such that, after anchoring this sample,  
it becomes possible to salvage m logs in valid order.  
If already possible without it, return 0.  
If no sample helps, return −1.
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
