## Title
Festival Token Collection

## Slug
festival-token-collection

## Difficulty
Hard

## Description
A long bazaar stretches n vendor tables from left to right.  
Each vendor displays a bargain worth ai.

A bargain hunter aims to obtain exactly m bargains while moving strictly from the left toward the right.  
At each table they may either take the bargain or ignore it.  
However, the i-th bargain they take must have worth at least bi.

Before the expedition, they may optionally add one highlight item once:  
they may place a single new item of any integer worth k at any table position  
(before the first, after the last, or between tables).

Your task is to determine the smallest integer k such that, after adding this highlight,  
it becomes possible to obtain m bargains in order.  
If already possible with no highlight, return 0.  
If no highlight can help, return −1.
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
