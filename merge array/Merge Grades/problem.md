## Title

Merge Grades

## Slug

merge-grades

## Difficulty


## Description

You are a teacher merging sorted grade lists from two sections of a class. Each list is represented by arrays `nums1` and `nums2`.  

Your task is to combine both into one sorted gradebook in non-decreasing order.




## Examples

### 1

#### Input

3
40 60 80
3
50 70 90

#### Output

40 50 60 70 80 90

#### Explanation

After merging, the final gradebook is [40,50,60,70,80,90].


### 2

#### Input

1
100
0

#### Output

100

#### Explanation

Only one section submitted grades, so the merged result is [100].


## Input Format  

- First line: integer `n` — number of grades in the first section (`nums1`)  
- Second line: `n` integers — grades in non-decreasing order  
- Third line: integer `m` — number of grades in the second section (`nums2`)  
- Fourth line: `m` integers — grades in non-decreasing order  


## Output Format  

Return the merged grade list in non-decreasing order.


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
