## Title

Merge Packets

## Slug

merge-packets

## Difficulty


## Description

You are processing network data from two routers. Each router outputs sorted packet IDs, stored in arrays `nums1` and `nums2`.  

Your task is to merge both packet streams into one ordered sequence.




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

The merged packet stream becomes [1,2,3,4,5,6].


### 2

#### Input

1
7
0

#### Output

7

#### Explanation

Only one router has packets, so the list remains [7].


## Input Format  

- First line: integer `n` — number of packets in the first router (`nums1`)  
- Second line: `n` integers — packet IDs in non-decreasing order  
- Third line: integer `m` — number of packets in the second router (`nums2`)  
- Fourth line: `m` integers — packet IDs in non-decreasing order  


## Output Format  

Return the merged list of packet IDs in non-decreasing order.


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
