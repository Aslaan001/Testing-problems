## Title
Cargo Bay Curations

## Slug
cargo-bay-curations

## Difficulty
Hard

## Description
A long coral bank holds n specimens arranged left to right.  
Each specimen has a health score ai.

A marine biologist needs to pick exactly m specimens while moving strictly from the leftmost reef toward the right.  
When they encounter a specimen, they may either take it or leave it.  
However, the i-th specimen they take must have health at least bi.

Before diving, they may optionally introduce a single surrogate specimen once:  
they may place a single new specimen with any integer health k at any position  
(before the first specimen, after the last specimen, or between existing specimens).

Your task is to determine the smallest integer k such that, after inserting this surrogate,  
it becomes possible to take m specimens in valid order.  
If already possible with no surrogate, return 0.  
If no surrogate can help, return −1.
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
