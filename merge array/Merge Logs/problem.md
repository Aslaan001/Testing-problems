## Title

Merge Logs

## Slug

merge-logs

## Difficulty


## Description

You are a system engineer merging log entries from two servers. Each log list is sorted chronologically and stored in arrays `nums1` and `nums2`.  

Your task is to merge both server logs into a single chronological log file.




## Examples

### 1

#### Input

3
1 4 8
3
2 5 9

#### Output

1 2 4 5 8 9

#### Explanation

After merging both server logs, the final log order is [1,2,4,5,8,9].


### 2

#### Input

1
3
0

#### Output

3

#### Explanation

Only one log file exists, so the merged list remains the same.


## Input Format  

- First line: integer `n` — number of logs in the first server (`nums1`)  
- Second line: `n` integers — timestamps in non-decreasing order  
- Third line: integer `m` — number of logs in the second server (`nums2`)  
- Fourth line: `m` integers — timestamps in non-decreasing order  


## Output Format  

Return the merged server log list in non-decreasing order.


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
