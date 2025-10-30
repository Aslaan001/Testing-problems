## Title

Merge Files

## Slug

merge-files

## Difficulty


## Description

You are a system administrator combining two sorted lists of file timestamps. Each list represents files stored in chronological order, given as integer arrays `nums1` and `nums2`.  

Your task is to merge both lists into one complete chronological file log.




## Examples

### 1

#### Input

3
1 3 5
3
2 4 6

#### Output

1 2 3 4 5 6

#### Explanation

After merging both file lists, the combined log becomes [1,2,3,4,5,6].


### 2

#### Input

2
5 9
0

#### Output

5 9

#### Explanation

The second list is empty, so the merged list remains unchanged.


## Input Format  

- First line: integer `n` — number of timestamps in the first list (`nums1`)  
- Second line: `n` integers — timestamps in non-decreasing order  
- Third line: integer `m` — number of timestamps in the second list (`nums2`)  
- Fourth line: `m` integers — timestamps in non-decreasing order  


## Output Format  

Return the merged list of timestamps in non-decreasing order.


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
