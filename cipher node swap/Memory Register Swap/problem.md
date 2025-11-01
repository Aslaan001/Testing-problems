## Title
Memory Register Swap

## Slug
memory-register-swap

## Difficulty
Medium

## Description
Inside a quantum CPU, memory registers are lined up sequentially.  
Your task is to swap the `kth register from the start` and `kth register from the end` for load balancing.  

Return the updated memory register chain.

## Examples
### 1 
#### Input
6  
4 2 9 8 5 7  
3

#### Output
4 2 5 8 9 7

#### Explanation
Swapped 3rd register from start (`9`) with 3rd from end (`5`).

## Input Format
- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the balanced register chain.

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
