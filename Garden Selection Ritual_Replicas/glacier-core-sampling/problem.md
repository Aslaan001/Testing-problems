## Title
Glacier Core Sampling

## Slug
glacier-core-sampling

## Difficulty
Hard

## Description
A long apple row called the Orchard of Echoes has n trees aligned left to right.  
Each fruit radiates a tone ai.

A musician wants to pluck exactly m fruits while moving strictly from the left orchard toward the right.  
When they reach a tree, they may pluck its fruit or skip it.  
However, the i-th fruit they pluck must have tone at least bi.

Before the run, they may optionally graft one harmonizing tree once:  
they may add a single new tree with any integer tone k at any spot  
(before the first tree, after the last, or between trees).

Your task is to determine the smallest integer k such that, after grafting this harmonizer,  
it becomes possible to pluck m fruits in valid order.  
If already possible with no graft, return 0.  
If no harmonizer helps, return −1.
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
