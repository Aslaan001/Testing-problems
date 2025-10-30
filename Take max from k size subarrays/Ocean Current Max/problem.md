## Title
Ocean Current Max

## Slug
ocean-current-max

## Difficulty
Easy

## Description
Scientists measure ocean current speeds in knots.  
Your task is to find the `maximum sum of speeds` across any `k` consecutive measurements`.

Return that maximum flow strength.

## Examples

### 1
#### Input
6
4 1 2 10 2 3
3

#### Output
15

#### Explanation
Current flow groups: `[4,1,2]=7`, `[1,2,10]=13`, `[2,10,2]=14`, `[10,2,3]=15`.  
Maximum = `15`.

## Input Format
- First line: integer `n` — number of readings.  
- Second line: `n` integers — current speeds.  
- Third line: integer `k` — size of group.

## Output Format
Integer — maximum flow strength.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ current[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
