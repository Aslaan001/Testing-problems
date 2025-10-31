## Title

Magic Stone Pairing

## Slug

magic-stone-pairing

## Difficulty

Medium

## Description

In the land of Arithma, mages have `n` enchanted stones, each holding an integer power value.  
They wish to pair the stones so that the `sum of each pair’s powers is divisible by a sacred number 'k'`.

Determine whether this perfect pairing is possible.  
Return `"YES"` if it can be done, otherwise return `"NO"`.

### Example 1

#### Input
4  
9 7 5 3  
6

#### Output
YES

#### Explanation
Possible pairs: `(9,3)` and `(7,5)` both have sums divisible by `6`.

### Example 2

#### Input
4  
92 75 65 48  
10

#### Output
YES

## Input Format

- First line: integer `n`.  
- Second line: `n` integers — power values.  
- Third line: integer `k`.

## Output Format

- `"YES"` if pairs can be formed where each pair’s sum is divisible by `k`.  
- Otherwise, `"NO"`.

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
