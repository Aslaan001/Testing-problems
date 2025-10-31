## Title

Pairs of Harmony

## Slug

pairs-of-harmony

## Difficulty

Medium

## Description

In an ancient manuscript, numbers represent sounds of harmony.  
You must find out if it’s possible to pair the sounds so that every pair’s combined resonance (sum) is perfectly divisible by `k`.  

If it can be done, return `"YES"`. Otherwise, return `"NO"`.

### Example 1

#### Input
4  
9 7 5 3  
6

#### Output
YES

#### Explanation
The pairs `(9,3)` and `(7,5)` both produce harmonic resonance divisible by 6.

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

- `"YES"` if harmony pairs exist, `"NO"` otherwise.

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
