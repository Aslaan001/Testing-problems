## Title

Merge Races

## Slug

merge-races

## Difficulty


## Description

You are an event organizer combining finish times from two races. Each list of race times is sorted in non-decreasing order, represented by arrays `nums1` and `nums2`.  

Your task is to merge both race results into a single sorted leaderboard.




## Examples

### 1

#### Input

3
10 15 20
3
12 17 25

#### Output

10 12 15 17 20 25

#### Explanation

Merging both races’ times gives [10,12,15,17,20,25].


### 2

#### Input

1
9
0

#### Output

9

#### Explanation

Only one race result exists, so it remains unchanged.


## Input Format  

- First line: integer `n` — number of times in the first list (`nums1`)  
- Second line: `n` integers — times in non-decreasing order  
- Third line: integer `m` — number of times in the second list (`nums2`)  
- Fourth line: `m` integers — times in non-decreasing order  


## Output Format  

Return the merged race leaderboard in non-decreasing order.


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
