## Title

Merge Books

## Slug

merge-books

## Difficulty


## Description

You are a librarian merging book ID lists from two branches. Each list is sorted in non-decreasing order, represented by arrays `nums1` and `nums2`.  

Your task is to merge both branches’ catalogues into one sorted master list.




## Examples

### 1

#### Input

3
10 20 30
3
15 25 35

#### Output

10 15 20 25 30 35

#### Explanation

The final catalogue after merging is [10,15,20,25,30,35].


### 2

#### Input

1
5
0

#### Output

5

#### Explanation

The second branch has no books, so the catalogue remains unchanged.


## Input Format  

- First line: integer `n` — number of books in the first list (`nums1`)  
- Second line: `n` integers — book IDs in non-decreasing order  
- Third line: integer `m` — number of books in the second list (`nums2`)  
- Fourth line: `m` integers — book IDs in non-decreasing order  


## Output Format  

Return the merged book list in non-decreasing order.


## Constraints  

- 1 ≤ n ≤ 100  
- 1 ≤ nums1[i] ≤ 1e9  
- 1 ≤ m ≤ 100  
- 1 ≤ nums2[i] ≤ 1e9  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays.
