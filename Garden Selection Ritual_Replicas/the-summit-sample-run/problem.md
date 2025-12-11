## Title
The Summit Sample Run

## Slug
the-summit-sample-run

## Difficulty
Hard

## Description
A long ridgeway contains n sampling spots arranged left to right.  
Each spot yields a sample value ai.

A researcher must collect exactly m samples while moving strictly from the left zone toward the right.  
When they reach a spot, they may either collect the sample or skip it.  
However, the i-th sample they collect must have value at least bi.

Before starting the sampling run, they may optionally place one calibration sample once:  
they may insert a single new sample of any integer value k at any position  
(before the first spot, after the last spot, or between spots).

Your task is to determine the smallest integer k such that, after inserting the calibration sample,  
it becomes possible to collect m samples in the intended order.  
If already possible without calibration, return 0.  
If no calibration sample can help, return −1.
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
