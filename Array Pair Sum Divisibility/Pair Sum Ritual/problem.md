## Title

Pair Sum Ritual

## Slug

pair-sum-ritual

## Difficulty

Medium

## Description

During a magical ritual, the sorcerer must group energy crystals into pairs.  
Each pair’s combined energy must be divisible by `k`.

Determine whether this is possible for the given list of crystals.  
Return `"YES"` if the ritual can be completed, otherwise `"NO"`.

### Example 1

#### Input
4  
9 7 5 3  
6

#### Output
YES

### Example 2

#### Input
4  
92 75 65 48  
10

#### Output
YES

## Input Format

- Line 1: integer `n`.  
- Line 2: `n` integers — crystal energies.  
- Line 3: integer `k`.

## Output Format

- `"YES"` if valid pairs can be formed.  
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
