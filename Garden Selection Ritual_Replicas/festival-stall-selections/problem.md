## Title
Festival Stall Selections

## Slug
festival-stall-selections

## Difficulty
Hard

## Description
A long row of festival stalls stretches n booths from left to right.  
Each stall offers an item of value ai.

A visitor wants to purchase exactly m items while strolling strictly from the leftmost stall toward the right.  
When they reach a stall, they may either buy the item or move on.  
However, the i-th purchase must have value at least bi.

Before arriving, they may optionally commission a single bespoke item once:  
they may introduce a single new item of any integer value k into the lineup at any position  
(before the first stall, after the last stall, or between existing stalls).

Your task is to determine the smallest integer k such that, after adding this new item,  
it becomes possible to buy m items in valid order.  
If the visitor already meets the requirements with no added item, return 0.  
If no bespoke item can make it possible, return −1.
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
