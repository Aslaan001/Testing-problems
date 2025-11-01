## Title
Reverse Books on Shelf

## Slug
reverse-books-on-shelf

## Difficulty
Medium

## Description

A librarian arranges books on a shelf.  
You need to reverse the order of books between position `m` and `n`.

`Details:`  
* Positions are 1-indexed.  
* 1 ≤ m ≤ n ≤ total books.

## Examples

### 1
#### Input
5  
1 2 3 4 5  
2 4  

#### Output
1 4 3 2 5  

#### Explanation
Books 2–4 reversed → `4 -> 3 -> 2`.

### 2
#### Input
3  
1 2 3  
1 3  

#### Output
3 2 1  

#### Explanation
Full shelf reversed.

### 3
#### Input
1  
9  
1 1  

#### Output
9  

#### Explanation
Single book — no change.

## Input Format
- First line: integer `n` — number of books.  
- Second line: `n` integers representing book IDs.  
- Third line: two integers `m` and `n` — start and end.

## Output Format
Print all book IDs after rearrangement.

## Constraints
- 1 <= n <= 500  
- 1 <= m <= n  
- -5000 <= book.id <= 5000  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
linked-list, two-pointers, reversal
