## Title
Space Mineral Max

## Slug
space-mineral-max

## Difficulty
Easy

## Description
You are exploring an asteroid belt rich in minerals.  
Each reading shows the mineral density in a segment.  
Find the `maximum mineral concentration` in any `k` consecutive segments`.

Return the maximum found.

## Examples

### 1
#### Input
6
4 1 2 10 2 3
3

#### Output
15

#### Explanation
Segments: `[4,1,2]=7`, `[1,2,10]=13`, `[2,10,2]=14`, `[10,2,3]=15`.  
Maximum = `15`.

## Input Format
- First line: integer `n` — number of segments.  
- Second line: `n` integers — mineral values.  
- Third line: integer `k` — consecutive segments.

## Output Format
A single integer — maximum mineral sum.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ mineral[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
