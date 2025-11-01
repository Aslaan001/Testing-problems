## Title
Pipeline Segment Swap

## Slug
pipeline-segment-swap

## Difficulty
Medium

## Description
In an oil refinery, pipeline segments are connected in a chain.  
To fix a pressure issue, swap the `kth segment from the start` and the `kth segment from the end`.  

Return the repaired pipeline order.

## Examples
### 1 
#### Input
5  
3 4 5 6 7  
2

#### Output
3 6 5 4 7

#### Explanation
Swapped 2nd segment from start (`4`) and 2nd from end (`6`).

## Input Format
- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the repaired pipeline chain.

## Constraints
- 1 ≤ n ≤ 10^5  
- 1 ≤ k ≤ n  
- 0 ≤ node.val ≤ 100

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, arrays
