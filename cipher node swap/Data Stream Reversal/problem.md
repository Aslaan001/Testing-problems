## Title
Data Stream Reversal

## Slug
data-stream-reversal

## Difficulty
Medium

## Description
In a high-tech data facility, a continuous `Data Stream` of nodes flows endlessly.  
A malfunction caused two symmetric points to become corrupted.  

Your mission as the `Stream Engineer` is to swap the `kth packet from the start` and `kth packet from the end` of the data stream to restore stability.  

All positions are `1-based`.  
Return the corrected stream after the swap.

## Examples
### 1 
#### Input
5  
10 20 30 40 50  
2

#### Output
10 40 30 20 50

#### Explanation
Swap the 2nd packet from start (`20`) with 2nd from end (`40`).

## Input Format
- First line: integer `n` — the number of data packets.  
- Second line: `n` integers — packet values.  
- Third line: integer `k` — position to swap (1-based).

## Output Format
Return the head of the updated Data Stream.

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
