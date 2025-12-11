## Title
Desert Caravan Selection

## Slug
desert-caravan-selection

## Difficulty
Hard

## Description
A long caravan trail hosts n bundles laid out left to right.  
Each bundle has worth ai.

A trader desires to take exactly m bundles while traveling strictly from the trail's start toward the end.  
When they reach a bundle, they may either take it or leave it.  
However, the i-th bundle they take must have worth at least bi.

Before departure, they may optionally add one extra bundle once:  
they may place a single new bundle of any integer worth k at any position on the trail  
(before the first bundle, after the last bundle, or between existing bundles).

Your task is to determine the smallest integer k such that, after adding this bundle,  
it becomes possible to take m bundles in order.  
If no addition is needed, return 0.  
If adding any bundle cannot help, return −1.
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
