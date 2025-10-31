## Title

Sum Divisible Couples

## Slug

sum-divisible-couples

## Difficulty

Medium

## Description

In a math workshop, students must form pairs of numbers.  
Each pair’s total sum should be divisible by a given number `k`.  

Your task is to determine whether the array of numbers can be divided into such pairs.

Return `"YES"` if possible, otherwise `"NO"`.

### Example 1

#### Input
4  
9 7 5 3  
6

#### Output
YES

#### Explanation
Pairs `(9,3)` and `(7,5)` have sums divisible by 6.

### Example 2

#### Input
4  
92 75 65 48  
10

#### Output
YES

## Input Format

- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format

- `"YES"` if valid pairing possible, `"NO"` otherwise.

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
