## Title
Telescope Magnitude Check

## Slug
telescope-magnitude-check

## Difficulty
Easy

## Description
A telescope logs star magnitudes in `arr[]` across a scanning sweep. Due to processing, the recorded sequence should be non-decreasing. Verify this property. Output `true` if `arr[]` is in `non-decreasing order`, otherwise `false`.

### Example 1
#### Input
5  
1 1 2 2 3
#### Output
true

### Example 2
#### Input
5  
1 2 1 2 3
#### Output
false

## Input Format
- `n` — number of observations  
- `arr[]` — magnitudes

## Output Format
`true` or `false`

## Constraints
1 ≤ n ≤ 10⁶  
1 ≤ arr[i] ≤ 10⁶

## Tags
arrays, sorting
