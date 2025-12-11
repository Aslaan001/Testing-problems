## Title
The Workshop Toolchain

## Slug
the-workshop-toolchain

## Difficulty
Hard

## Description
A long cargo platform stores n containers arranged left to right.  
Each container notes a load rating ai.

A foreman must select exactly m containers while moving strictly from the platform's left toward the right.  
At each container they may either choose it or skip it.  
However, the i-th container chosen must have rating at least bi.

Before selection, they may optionally place one dummy container once:  
they may add a single new container with any integer rating k at any place  
(before the first, after the last, or between containers).

Your task is to determine the smallest integer k such that, after placing this dummy,  
it becomes possible to choose m containers in valid order.  
If already possible without it, return 0.  
If no dummy can help, return −1.
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
