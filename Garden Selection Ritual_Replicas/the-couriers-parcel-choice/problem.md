## Title
The Courier's Parcel Choice

## Slug
the-couriers-parcel-choice

## Difficulty
Hard

## Description
A long mobile library stop contains n titles arranged left to right.  
Each title carries appeal ai.

A patron needs to choose exactly m titles while moving strictly from the left stop to the right.  
When they examine any title, they may either take it or pass by.  
However, the i-th title they take must have appeal at least bi.

Before the tour, the librarian may optionally add one special edition once:  
they may insert a single new title of any integer appeal k at any stop  
(before the first title, after the last, or between titles).

Your task is to determine the smallest integer k such that, after adding this edition,  
it becomes possible to choose m titles in valid order.  
If already possible with no addition, return 0.  
If no edition can help, return −1.
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
