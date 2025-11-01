## Title
Music Beat Reorder

## Slug
music-beat-reorder

## Difficulty
Medium

## Description
A digital music track stores beats in a linked structure.  
The composer wants to remix it by swapping the `kth beat from the start` and the `kth beat from the end`.  

Return the updated beat sequence after remixing.

## Examples
### 1 
#### Input
6  
2 4 6 8 10 12  
3

#### Output
2 4 10 8 6 12

#### Explanation
Swapped 3rd beat from start (`6`) and 3rd from end (`10`).

## Input Format
- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the remixed beat sequence.

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
