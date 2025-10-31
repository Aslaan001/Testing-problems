## Title

Balance Energy Circuits

## Slug

balance-energy-circuits

## Difficulty

Medium

## Description

You are working with `n` electrical circuits, each with a specific energy rating.  
You must connect them in pairs so that the total energy of each pair is divisible by `k`.

Return `"YES"` if such pairing is possible; otherwise, return `"NO"`.

### Example 1

#### Input
4  
9 7 5 3  
6

#### Output
YES

#### Explanation
Pairs `(9,3)` and `(7,5)` are valid.

### Example 2

#### Input
4  
92 75 65 48  
10

#### Output
YES

## Input Format

- Line 1: integer `n`.  
- Line 2: `n` integers — energy ratings.  
- Line 3: integer `k`.

## Output Format

- `"YES"` if valid pairing possible, otherwise `"NO"`.

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
