## Title

Accounting Target Segment Analyzer

## Slug

accounting-target-segment-analyzer

## Difficulty

Medium

## Description

Transaction monitoring services frequently rely on cumulative behavior rather than isolated
events. By evaluating all adjacent intervals within a transaction array, the service can detect
how many of those intervals yield a total equal to a specific target. This count provides insight
into recurring financial patterns and balance conditions.

## Examples

### 1

#### Input

3  
1 1 1  
2

#### Output

2

#### Explanation

The subarrays with sum equal to 2 are:

- [1, 1] (indices 0 to 1)  
- [1, 1] (indices 1 to 2)

### 2

#### Input

3  
1 2 3  
3

#### Output

2

#### Explanation

The valid subarrays are:

- [1, 2]  
- [3]

## Input Format

- First line contains an integer n, the number of elements in the array.
- Second line contains n space-separated integers representing the array nums.
- Third line contains an integer k, the target sum.

## Output Format

- Return a single integer representing the number of subarrays whose sum equals k.

## Constraints

- 1 ≤ n ≤ 20000  
- -1000 ≤ nums[i] ≤ 1000  
- -10⁷ ≤ k ≤ 10⁷

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

array

## Company

quora
