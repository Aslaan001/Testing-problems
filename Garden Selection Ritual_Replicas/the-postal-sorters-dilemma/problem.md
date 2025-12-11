## Title
The Postal Sorter's Dilemma

## Slug
the-postal-sorters-dilemma

## Difficulty
Hard

## Description
A long sorting room has n incoming packages placed left to right.  
Each package has a durability ai.

A sorter must select exactly m packages while working strictly from the leftmost to the rightmost.  
At each package they may either select it or pass it by.  
However, the i-th chosen package must have durability at least bi.

Before operations begin, they may optionally insert one test package exactly once:  
they may add a single new package of any integer durability k at any position in the sequence  
(before the first package, after the last package, or between existing packages).

Your task is to determine the smallest integer k such that, after inserting this test package,  
it becomes possible to select m packages in the needed order.  
If selection is already possible with no added package, return 0.  
If no test package can help, return −1.
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
