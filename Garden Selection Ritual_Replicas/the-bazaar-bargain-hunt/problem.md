## Title
The Bazaar Bargain Hunt

## Slug
the-bazaar-bargain-hunt

## Difficulty
Hard

## Description
A long pasture contains n cattle pens aligned from left to right.  
Each pen holds a cow with yield ai.

A rancher wishes to select exactly m cattle while moving strictly from the left gate toward the right.  
When passing any pen, they may either select the cow or skip it.  
However, the i-th cow they select must have yield at least bi.

Before heading out, they may optionally introduce one stud cow once:  
they may place a single new cow with any integer yield k in any pen position  
(before the first pen, after the last pen, or between pens).

Your task is to determine the smallest integer k such that, after adding this stud,  
it becomes possible to select m cattle in valid order.  
If already possible without it, return 0.  
If no stud helps, return −1.
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
