## Title
Data Bandwidth Max

## Slug
data-bandwidth-max

## Difficulty
Easy

## Description
An engineer measures data transfer rates across network intervals.  
Find the `maximum total bandwidth` achieved in any `k` consecutive intervals`.

Return that maximum bandwidth.

## Examples

### 1
#### Input
5
1 2 3 4 5
2

#### Output
9

#### Explanation
Intervals: `[1,2]=3`, `[2,3]=5`, `[3,4]=7`, `[4,5]=9`.  
Maximum = `9`.

## Input Format
- First line: integer `n` — number of intervals.  
- Second line: `n` integers — bandwidth values.  
- Third line: integer `k` — consecutive intervals.

## Output Format
One integer — maximum bandwidth sum.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ bandwidth[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
