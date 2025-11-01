## Title
Energy Node Realignment

## Slug
energy-node-realignment

## Difficulty
Medium

## Description
In an energy core system, nodes transmit power in sequence.  
Due to an overload, swap the `kth node from start` and the `kth node from end` to rebalance the flow.  

Return the restructured energy chain.

## Examples
### 1 
#### Input
7  
3 6 9 12 15 18 21  
3

#### Output
3 6 15 12 9 18 21

#### Explanation
Swapped 3rd node from start (`9`) and 3rd from end (`15`).

## Input Format
- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the balanced energy chain.

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
