## Title
Galaxy Node Transposition

## Slug
galaxy-node-transposition

## Difficulty
Medium

## Description
In the `Andromeda Network`, nodes of energy form a galactic chain.  
You, as the `Space Coder`, must realign the nodes by swapping the `kth node from the start` and the `kth node from the end`.  

All indexing is `1-based`.  
Return the restructured chain.

## Examples
### 1 
#### Input
6  
9 8 7 6 5 4  
3

#### Output
9 8 5 6 7 4

#### Explanation
Swapped 3rd node from start (`7`) and 3rd from end (`5`).

## Input Format
- First line: integer `n` — number of energy nodes.  
- Second line: `n` integers — energy values.  
- Third line: integer `k`.

## Output Format
Return the restructured galaxy chain.

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
