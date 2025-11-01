## Title
Cipher Scroll Rearrange

## Slug
cipher-scroll-rearrange

## Difficulty
Medium

## Description
An ancient scroll contains encrypted runes connected in a chain.  
To read it correctly, swap the `kth rune from start` and the `kth rune from end`.  

Return the rearranged scroll.

## Examples
### 1 
#### Input
5  
5 9 7 8 6  
2

#### Output
5 8 7 9 6

#### Explanation
Swapped 2nd rune from start (`9`) and 2nd from end (`8`).

## Input Format
- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the rearranged cipher scroll.

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
