## Title
Alien Signal Reorder

## Slug
alien-signal-reorder

## Difficulty
Medium

## Description
An alien transmission arrives as a chain of coded nodes.  
To decrypt it, you must swap the `kth signal from the start` and the `kth signal from the end` to restore correct frequency order.  

Return the decoded chain.

## Examples
### 1 
#### Input
5  
9 8 7 6 5  
2

#### Output
9 6 7 8 5

#### Explanation
Swapped 2nd signal from start (`8`) and 2nd from end (`6`).

## Input Format
- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the decoded signal chain.

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
