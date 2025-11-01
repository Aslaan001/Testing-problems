## Title
Portal Node Rearrange

## Slug
portal-node-rearrange

## Difficulty
Medium

## Description
In the realm of `Portalis`, teleportation gates are connected in sequence.  
To stabilize the portal field, swap the `kth gate from the start` and the `kth gate from the end`.  

Return the stabilized portal chain.

## Examples
### 1 
#### Input
6  
1 2 3 4 5 6  
2

#### Output
1 5 3 4 2 6

#### Explanation
Swapped 2nd gate from start (`2`) and 2nd from end (`5`).

## Input Format
- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the balanced portal chain.

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
