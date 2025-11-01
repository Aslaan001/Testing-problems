## Title
River Flow Correction

## Slug
river-flow-correction

## Difficulty
Medium

## Description
A mystical river’s flow is represented as a chain of currents (nodes).  
When imbalance occurs, you must swap the `kth flow from the start` and the `kth flow from the end` to restore harmony.  

Return the balanced river chain.

## Examples
### 1 
#### Input
5  
1 3 5 7 9  
2

#### Output
1 7 5 3 9

#### Explanation
Swapped 2nd flow from start (`3`) and 2nd from end (`7`).

## Input Format
- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the updated river flow.

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
