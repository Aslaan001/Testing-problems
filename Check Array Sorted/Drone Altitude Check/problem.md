## Title
Drone Altitude Check

## Slug
drone-altitude-check

## Difficulty
Easy

## Description
A drone’s altitude log `arr[]` is expected to climb or stay level during an ascent test. Verify that altitudes never drop. Return `true` if `arr[]` is in `non-decreasing order`; otherwise, return `false`.

### Example 1
#### Input
4  
100 100 120 130
#### Output
true

### Example 2
#### Input
4  
100 120 110 130
#### Output
false

## Input Format
- `n` — number of samples  
- `arr[]` — altitude samples

## Output Format
`true` or `false`

## Constraints
1 ≤ n ≤ 10⁶  
1 ≤ arr[i] ≤ 10⁶

## Tags
arrays, sorting
