## Title
Treasure Node Shift

## Slug
treasure-node-shift

## Difficulty
Medium

## Description
In the `Lost Mines`, treasure crates are connected in a chain.  
To unlock the vault, swap the `kth crate from the start` and `kth crate from the end`.  

Return the reordered treasure chain.

## Examples
### 1 
#### Input
5  
4 9 7 3 2  
2

#### Output
4 3 7 9 2

#### Explanation
Swapped 2nd crate from start (`9`) with 2nd from end (`3`).

## Input Format
- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the updated treasure chain.

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
