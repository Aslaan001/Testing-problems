## Title
Knight Queue Adjustment

## Slug
knight-queue-adjustment

## Difficulty
Medium

## Description
In a royal tournament, knights stand in a queue.  
To ensure fairness, the king orders you to swap the `kth knight from the front` and the `kth knight from the end`.  

Return the updated queue.

## Examples
### 1 
#### Input
5  
1 3 5 7 9  
2

#### Output
1 7 5 3 9

#### Explanation
Swapped 2nd knight from front (`3`) and 2nd from end (`7`).

## Input Format
- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the reordered knight queue.

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
