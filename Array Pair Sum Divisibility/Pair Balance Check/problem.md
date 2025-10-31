## Title

Pair Balance Check

## Slug

pair-balance-check

## Difficulty

Medium

## Description

A scientist is testing data pairs for balance.  
The data points can only be paired if the sum of each pair is divisible by a constant number `k`.  

Your task is to verify if such a pairing is possible.  
Return `"YES"` if every data point can be paired successfully, else `"NO"`.

### Example 1

#### Input
4  
9 7 5 3  
6

#### Output
YES

#### Explanation
Pairs `(9,3)` and `(7,5)` are balanced since their sums are divisible by 6.

### Example 2

#### Input
4  
92 75 65 48  
10

#### Output
YES

## Input Format

- First line: integer `n`.  
- Second line: array of integers.  
- Third line: integer `k`.

## Output Format

- `"YES"` if pairing possible, otherwise `"NO"`.

## Constraints

- 1 ≤ n ≤ 10⁵  
- 1 ≤ arr[i] ≤ 10⁹  
- 1 ≤ k ≤ 10⁹  
- `n` is even  

## Time Limit

1 second  

## Memory Limit

512 MB  

## Tags

arrays, sorting.
