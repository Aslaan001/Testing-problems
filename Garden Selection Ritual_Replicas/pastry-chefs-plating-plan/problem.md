## Title
Pastry Chef's Plating Plan

## Slug
pastry-chefs-plating-plan

## Difficulty
Hard

## Description
A long roadside antique row displays n treasures left to right.  
Each treasure has a provenance ai.

A museum buyer plans to acquire exactly m treasures while traveling strictly from left to right.  
When they pass any table, they may either acquire the treasure or leave it.  
However, the i-th treasure they acquire must have provenance at least bi.

Before the outing, they may optionally add one featured item once:  
they may place a single new treasure of any integer provenance k at any display location  
(before the first, after the last, or between items).

Your task is to determine the smallest integer k such that, after adding this featured item,  
it becomes possible to acquire m treasures in valid order.  
If already possible with no feature, return 0.  
If no featured item helps, return −1.
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
