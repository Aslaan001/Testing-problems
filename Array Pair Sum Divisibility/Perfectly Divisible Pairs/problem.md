## Title

Perfectly Divisible Pairs

## Slug

perfectly-divisible-pairs

## Difficulty

Medium

## Description

You are given an array of integers.  
Your task is to determine whether it’s possible to arrange the numbers into pairs so that each pair’s sum is perfectly divisible by a number `k`.

Return `"YES"` if possible, otherwise `"NO"`.

### Example 1

#### Input
4  
9 7 5 3  
6

#### Output
YES

#### Explanation
Pairs `(9,3)` and `(7,5)` are both valid since 12 and 12 are divisible by 6.

### Example 2

#### Input
4  
92 75 65 48  
10

#### Output
YES

## Input Format

- Line 1: integer `n`.  
- Line 2: `n` integers — array elements.  
- Line 3: integer `k`.

## Output Format

- Return `"YES"` if possible, `"NO"` otherwise.

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
