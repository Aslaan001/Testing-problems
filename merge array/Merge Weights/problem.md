## Title

Merge Weights

## Slug

merge-weights

## Difficulty


## Description

You are handling shipment data with recorded package weights. Two lists of package weights are sorted and stored as arrays `nums1` and `nums2`.  

Your task is to merge both lists into one sorted shipment list.




## Examples

### 1

#### Input

3
2 5 8
3
1 4 9

#### Output

1 2 4 5 8 9

#### Explanation

After merging, the combined weight list becomes [1,2,4,5,8,9].


### 2

#### Input

1
10
0

#### Output

10

#### Explanation

The second list is empty, so the merged list remains [10].


## Input Format  

- First line: integer `n` — number of packages in the first list (`nums1`)  
- Second line: `n` integers — weights in non-decreasing order  
- Third line: integer `m` — number of packages in the second list (`nums2`)  
- Fourth line: `m` integers — weights in non-decreasing order  


## Output Format  

Return the merged list of package weights in non-decreasing order.


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
