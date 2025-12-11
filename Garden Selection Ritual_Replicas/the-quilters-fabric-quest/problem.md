## Title
The Quilter's Fabric Quest

## Slug
the-quilters-fabric-quest

## Difficulty
Hard

## Description
A long gallery holds n artworks displayed left to right.  
Each work has a rating ai.

A curator wants to acquire exactly m works while moving strictly from the gallery's left wing toward the right.  
When they arrive at a piece, they may either acquire it or continue.  
However, the i-th work they acquire must have rating at least bi.

Before the acquisition tour, they may optionally commission one commissioned piece once:  
they may add a single new artwork of any integer rating k at any display spot  
(before the first, after the last, or between artworks).

Your task is to determine the smallest integer k such that, after commissioning this piece,  
it becomes possible to acquire m works in valid order.  
If acquisition is already possible without commission, return 0.  
If no commissioned piece helps, return −1.
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
