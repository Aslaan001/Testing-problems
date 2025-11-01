## Title
Ocean Bubble Swap

## Slug
ocean-bubble-swap

## Difficulty
Medium

## Description
In the deep sea, bubbles form a linear chain.  
To stabilize pressure, you must swap the `kth bubble from the surface` and the `kth bubble from the depth`.  

Return the balanced bubble chain.

## Examples
### 1 
#### Input
5  
2 4 6 8 10  
2

#### Output
2 8 6 4 10

#### Explanation
Swapped 2nd bubble from surface (`4`) and 2nd from depth (`8`).

## Input Format
- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the balanced bubble order.

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
