## Title
Courier's Timed Pickups

## Slug
couriers-timed-pickups

## Difficulty
Hard

## Description
A long base camp supply row stores n expedition kits left to right.  
Each kit scores ai.

A team must requisition exactly m kits while moving strictly from the left cache toward the right.  
When they reach a kit, they may either take it or leave it.  
However, the i-th kit they take must have score at least bi.

Before deployment, they may optionally add one bonus kit once:  
they may add a single new kit with any integer score k at any position  
(before the first, after the last, or between kits).

Your task is to determine the smallest integer k such that, after adding this bonus kit,  
it becomes possible to requisition m kits in valid order.  
If already possible with no bonus, return 0.  
If no bonus kit helps, return −1.
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
