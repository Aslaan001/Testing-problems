## Title

Merge Timestamps

## Slug

merge-timestamps

## Difficulty


## Description

You are analyzing event timestamps from two monitoring systems. Each list is sorted in non-decreasing order, represented as arrays `nums1` and `nums2`.  

Your task is to merge both timestamp lists into one continuous timeline.




## Examples

### 1

#### Input

3
1 5 9
3
2 6 10

#### Output

1 2 5 6 9 10

#### Explanation

After merging, the timeline becomes [1,2,5,6,9,10].


### 2

#### Input

1
3
0

#### Output

3

#### Explanation

One system has no data, so the merged list remains unchanged.


## Input Format  

- First line: integer `n` — number of timestamps in the first list (`nums1`)  
- Second line: `n` integers — timestamps in non-decreasing order  
- Third line: integer `m` — number of timestamps in the second list (`nums2`)  
- Fourth line: `m` integers — timestamps in non-decreasing order  


## Output Format  

Return the merged timeline in non-decreasing order.


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
