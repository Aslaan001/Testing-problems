## Title
Mountain Trail Gem Hunt

## Slug
mountain-trail-gem-hunt

## Difficulty
Hard

## Description
A winding mountain trail contains n gem deposits aligned from left to right.  
Each deposit contains a gem with clarity ai.

A climber aims to take exactly m gems while hiking strictly from the trailhead toward the summit.  
When they encounter any deposit, they may either take a gem or bypass it.  
However, the i-th gem they take must have clarity at least bi.

Before beginning the ascent, they may optionally add one artificial deposit exactly once:  
they may place a single new gem of any integer clarity k at any spot on the trail  
(before the first deposit, after the last deposit, or between existing deposits).

Your task is to determine the smallest integer k such that, after inserting this new gem,  
it becomes possible to collect m gems in valid order.  
If the climber already meets the requirements with no added gem, return 0.  
If adding any gem cannot help, return −1.
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
