## Title

Merge Archives

## Slug

merge-archives

## Difficulty


## Description

You are an archivist tasked with combining two old library catalogues. Each catalogue is represented by an integer array `nums1` and `nums2`, both sorted in non-decreasing order, where each number represents the publication year of a book.

Your task is to merge both catalogues into a single chronological list of all books, sorted by publication year.




## Examples

### 1

#### Input

3
1990 1995 2000
3
1985 1995 2010

#### Output

1985 1990 1995 1995 2000 2010

#### Explanation

The two catalogues [1990,1995,2000] and [1985,1995,2010] merge into [1985,1990,1995,1995,2000,2010].


### 2

#### Input

2
2005 2020
0

#### Output

2005 2020

#### Explanation

The second catalogue is empty, so the merged list remains [2005,2020].


## Input Format  

- First line: integer `n` — number of entries in the first catalogue (`nums1`)  
- Second line: `n` integers — publication years in non-decreasing order  
- Third line: integer `m` — number of entries in the second catalogue (`nums2`)  
- Fourth line: `m` integers — publication years in non-decreasing order  


## Output Format  

Return the merged catalogue list with all years in non-decreasing order.


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
