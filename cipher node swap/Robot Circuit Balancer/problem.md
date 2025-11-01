## Title
Robot Circuit Balancer

## Slug
robot-circuit-balancer

## Difficulty
Medium

## Description
In a robot’s central system, data nodes in a circuit must remain balanced.  
Your job as the `Circuit Tuner` is to swap the `kth node from the front` and `kth node from the back` to maintain stability.

## Examples
### 1 
#### Input
5  
5 3 9 6 8  
2

#### Output
5 6 9 3 8

#### Explanation
Swapped 2nd node from start (`3`) and 2nd from end (`6`).

## Input Format
- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the stabilized circuit.

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
