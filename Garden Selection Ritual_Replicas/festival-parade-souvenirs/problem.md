## Title
Festival Parade Souvenirs

## Slug
festival-parade-souvenirs

## Difficulty
Hard

## Description
A long vintage market lane features n stalls aligned left to right.  
Each stall offers a relic ai.

A shopper aims to collect exactly m relics while moving strictly from the left entrance toward the right.  
When they encounter a relic, they may either add it to their bag or pass.  
However, the i-th relic they take must have relic value at least bi.

Before shopping, they may optionally insert one spotlight relic once:  
they may place a single new relic with any integer value k at any stall  
(before the first, after the last, or between stalls).

Your task is to determine the smallest integer k such that, after inserting this spotlight relic,  
it becomes possible to collect m relics in valid order.  
If already possible without it, return 0.  
If no spotlight helps, return −1.
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
