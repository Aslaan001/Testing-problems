## Title

Merge Orders

## Slug

merge-orders

## Difficulty


## Description

You are a store manager consolidating online and offline orders. Each order list is sorted by ID, represented as arrays `nums1` and `nums2`.  

Your task is to merge both order lists into one sorted list for fulfillment.




## Examples

### 1

#### Input

3
1 3 7
3
2 4 8

#### Output

1 2 3 4 7 8

#### Explanation

Merging the two order lists gives [1,2,3,4,7,8].


### 2

#### Input

1
10
0

#### Output

10

#### Explanation

Only one list has orders, so it remains unchanged.


## Input Format  

- First line: integer `n` — number of orders in the first list (`nums1`)  
- Second line: `n` integers — IDs in non-decreasing order  
- Third line: integer `m` — number of orders in the second list (`nums2`)  
- Fourth line: `m` integers — IDs in non-decreasing order  


## Output Format  

Return the merged order list in non-decreasing order.


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
