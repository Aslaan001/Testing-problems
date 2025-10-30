## Title

Merge Loot 2

## Slug

merge-loot-2

## Difficulty


## Description

You are a treasure hunter merging two collections of rare items. Each collection is represented as arrays `nums1` and `nums2`, sorted by value.  

Your task is to merge them into a single treasure list sorted in non-decreasing order.




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

The combined treasure list after merging is [1,2,3,4,5,6].


### 2

#### Input

1
10
0

#### Output

10

#### Explanation

Only one treasure collection exists, so it remains unchanged.


## Input Format  

- First line: integer `n` — number of items in the first collection (`nums1`)  
- Second line: `n` integers — values in non-decreasing order  
- Third line: integer `m` — number of items in the second collection (`nums2`)  
- Fourth line: `m` integers — values in non-decreasing order  


## Output Format  

Return the merged loot list in non-decreasing order.


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
