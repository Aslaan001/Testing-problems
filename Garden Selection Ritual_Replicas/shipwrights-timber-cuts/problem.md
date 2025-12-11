## Title
Shipwright's Timber Cuts

## Slug
shipwrights-timber-cuts

## Difficulty
Hard

## Description
A long shipyard bench contains n planks aligned from left to right.  
Each plank has grain quality ai.

A shipwright must select exactly m planks while moving strictly from the leftmost pile toward the right.  
When they find any plank, they may either take it or leave it.  
However, the i-th plank they select must have grain quality at least bi.

Before work begins, they may optionally craft one trial plank once:  
they may add a single new plank of any integer quality k at any position in the bench  
(before the first plank, after the last plank, or between existing planks).

Your task is to determine the smallest integer k such that, after placing this trial plank,  
it becomes possible to select m planks in valid order.  
If selection is possible without the trial plank, return 0.  
If no trial plank can help, return −1.
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
