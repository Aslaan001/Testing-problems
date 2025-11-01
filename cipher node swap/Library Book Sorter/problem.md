## Title
Library Book Sorter

## Slug
library-book-sorter

## Difficulty
Medium

## Description
A magical bookshelf organizes books in a single linked sequence.  
Due to a misplacement, you must swap the `kth book from the start` and the `kth book from the end` to restore order.  

Return the corrected sequence.

## Examples
### 1 
#### Input
5  
11 12 13 14 15  
2

#### Output
11 14 13 12 15

#### Explanation
Swapped 2nd book from start (`12`) with 2nd from end (`14`).

## Input Format
- First line: integer `n`.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the corrected bookshelf order.

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
