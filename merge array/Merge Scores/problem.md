## Title

Merge Scores

## Slug

merge-scores

## Difficulty


## Description

You are a teacher combining two sorted score lists from different tests. Each list is represented by arrays `nums1` and `nums2`.  

Your task is to merge both into one sorted score sheet in non-decreasing order.




## Examples

### 1

#### Input

3
30 50 70
3
40 60 80

#### Output

30 40 50 60 70 80

#### Explanation

After merging the test scores, you get [30,40,50,60,70,80].


### 2

#### Input

1
100
0

#### Output

100

#### Explanation

The second test has no scores, so the merged result is [100].


## Input Format  

- First line: integer `n` — number of scores in the first list (`nums1`)  
- Second line: `n` integers — scores in non-decreasing order  
- Third line: integer `m` — number of scores in the second list (`nums2`)  
- Fourth line: `m` integers — scores in non-decreasing order  


## Output Format  

Return the merged score list in non-decreasing order.


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
