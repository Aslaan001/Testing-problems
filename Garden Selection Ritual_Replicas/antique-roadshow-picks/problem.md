## Title
Antique Roadshow Picks

## Slug
antique-roadshow-picks

## Difficulty
Hard

## Description
A long highway flea market displays n antiques arranged left to right.  
Each item bears an appraisal ai.

A collector wants to secure exactly m antiques while driving strictly from the leftmost table toward the right.  
When passing any table, they may either secure an item or skip it.  
However, the i-th antique they secure must have appraisal at least bi.

Before the drive, they may optionally include one promotional piece once:  
they may introduce a single new item of any integer appraisal k at any spot in the display  
(before the first item, after the last item, or between items).

Your task is to determine the smallest integer k such that, after adding this piece,  
it becomes possible to secure m antiques in order.  
If already possible without it, return 0.  
If no promotional piece helps, return −1.
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
