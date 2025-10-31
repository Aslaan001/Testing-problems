## Title

Library Insertion Index

## Slug

library-insertion-index

## Difficulty

Medium

## Description

You are maintaining a digital library catalog where every book’s unique ID is stored in sorted order.  
A new book arrives with a specific ID number, and you must find the position where it should be inserted so that the catalog remains sorted.

Use `binary search` for efficient placement.

Return the `0-based index` where the new book ID should be inserted.

## Examples

### 1

#### Input

5 4
1 3 5 6 8

#### Output
2

#### Explanation

Book ID `4` should be placed at index `2`: `[1, 3, 4, 5, 6, 8]`.

### 2

#### Input

4 1
2 4 6 8 

#### Output
0

#### Explanation

Book ID `1` should be inserted at index `0`: `[1, 2, 4, 6, 8]`.

## Input Format  

- First line: two integers `n` and `key` — number of book IDs and the new book ID.  
- Second line: `n` space-separated integers — the sorted catalog.

## Output Format  

- A single integer — the index where the new book should be inserted.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  
- The catalog is sorted in ascending order with unique IDs.  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
