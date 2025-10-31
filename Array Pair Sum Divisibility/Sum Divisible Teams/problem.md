## Title

Sum Divisible Teams

## Slug

sum-divisible-teams

## Difficulty

Medium

## Description

You are organizing a coding event and have `n` players with different skill levels.  
You want to form teams of two players each, such that the `sum of their skill levels` is divisible by `k`.

If this is possible, return `"YES"`, otherwise `"NO"`.

### Example 1

#### Input
4  
9 7 5 3  
6

#### Output
YES

#### Explanation
Pairs `(9,3)` and `(7,5)` satisfy divisibility by 6.

### Example 2

#### Input
4  
92 75 65 48  
10

#### Output
YES

## Input Format

- First line: integer `n`.  
- Second line: `n` integers — skill levels.  
- Third line: integer `k`.

## Output Format

- `"YES"` if teams can be formed, `"NO"` otherwise.

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
