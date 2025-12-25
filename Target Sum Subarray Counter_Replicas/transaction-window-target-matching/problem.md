## Title

Transaction Window Target Matching

## Slug

transaction-window-target-matching

## Difficulty

Medium

## Description

A reporting module evaluates numeric arrays representing transaction flows. To validate
financial assumptions, the module searches for continuous intervals whose aggregated value is
exactly equal to a given benchmark. The challenge lies in identifying all such intervals without
overlooking overlapping or repeated patterns.

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
