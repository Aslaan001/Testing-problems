## Title

Merge Sensors

## Slug

merge-sensors

## Difficulty


## Description

You are analyzing readings from two weather sensors, each recording data in sorted order of time. The readings are represented by integer arrays `nums1` and `nums2`.  

Your task is to merge the readings into one complete chronological dataset.




## Examples

### 1

#### Input

3
2 4 8
3
1 3 9

#### Output

1 2 3 4 8 9

#### Explanation

After merging both sensors’ readings, you get [1,2,3,4,8,9].


### 2

#### Input

1
5
0

#### Output

5

#### Explanation

The second sensor has no readings, so the merged result remains [5].


## Input Format  

- First line: integer `n` — number of readings in the first sensor (`nums1`)  
- Second line: `n` integers — readings in non-decreasing order  
- Third line: integer `m` — number of readings in the second sensor (`nums2`)  
- Fourth line: `m` integers — readings in non-decreasing order  


## Output Format  

Return the merged sensor readings in non-decreasing order.


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
