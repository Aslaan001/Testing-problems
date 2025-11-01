## Title
Mirror Chain Exchange

## Slug
mirror-chain-exchange

## Difficulty
Medium

## Description
In the realm of `MirrorWorld`, there’s a magical `Mirror Chain` made of nodes reflecting each other’s essence.  

You, the `Mirror Keeper`, must perform a sacred ritual:  
Swap the `kth node from the beginning` with the `kth node from the end` to restore perfect balance.  

The chain follows `1-based indexing`.  
Return the `updated Mirror Chain` after the ritual.

## Examples
### 1 
#### Input
5  
1 2 3 4 5  
2

#### Output
1 4 3 2 5

#### Explanation
Original chain: `1->2->3->4->5`  
Swap the 2nd node from start (`2`) with 2nd node from end (`4`).  
Updated chain: `1->4->3->2->5`

## Input Format
- First line: integer `n` — number of nodes in the Mirror Chain.  
- Second line: `n` integers — the node data values.  
- Third line: integer `k` — position to swap (1-based).

## Output Format
Return the head of the updated Mirror Chain.

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
