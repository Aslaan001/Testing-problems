## Title
The Conveyor of Curiosities

## Slug
the-conveyor-of-curiosities

## Difficulty
Hard

## Description
A long conveyor belt carries n curiosities placed from left to right.  
Each item has a rarity value ai.

A collector wants to pick exactly m items while moving strictly from the left end toward the right.  
When they reach an item, they may either take it or leave it.  
However, the i-th item they pick must have rarity at least bi.

Before starting, they may optionally perform a single enhancement once:  
they may craft a single new curiosity of any integer rarity k, and insert it at any position on the belt  
(before the first item, after the last item, or between existing items).

Your task is to determine the smallest integer k such that, after inserting this new item,  
it becomes possible to pick m items in valid order.  
If the collector can already meet the requirements with no added item, return 0.  
If no choice of k can make the task possible, return −1.
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
