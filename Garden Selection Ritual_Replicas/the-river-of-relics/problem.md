## Title
The River of Relics

## Slug
the-river-of-relics

## Difficulty
Hard

## Description
A long river flows by n relics drifting from left to right along a bank.  
Each relic has an age value ai.

A scavenger wants to collect exactly m relics while moving strictly downstream from the leftmost bank toward the right.  
When they reach any relic, they may either scoop it up or let it pass.  
However, the i-th relic they take must have age at least bi.

Before they set out, they may optionally perform a restoration once:  
they may fabricate a single new relic of any integer age k, and drop it at any position along the bank  
(before the first relic, after the last relic, or between existing relics).

Your task is to determine the smallest integer k such that, after adding this new relic,  
it becomes possible to collect m relics in valid order.  
If the scavenger already meets the requirements with no added relic, return 0.  
If no fabricated relic can help, return −1.
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
