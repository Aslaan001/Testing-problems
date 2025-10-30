## Title

Merge Prices

## Slug

merge-prices

## Difficulty


## Description

You are a shopkeeper combining price lists from two suppliers. Each list, represented as `nums1` and `nums2`, is sorted in non-decreasing order.  

Your task is to merge both lists into a single sorted price catalogue.




## Examples

### 1

#### Input

3
100 200 400
3
150 300 500

#### Output

100 150 200 300 400 500

#### Explanation

After merging both supplier lists, the final catalogue is [100,150,200,300,400,500].


### 2

#### Input

1
250
0

#### Output

250

#### Explanation

The second list is empty, so the catalogue remains [250].


## Input Format  

- First line: integer `n` — number of prices in the first list (`nums1`)  
- Second line: `n` integers — prices in non-decreasing order  
- Third line: integer `m` — number of prices in the second list (`nums2`)  
- Fourth line: `m` integers — prices in non-decreasing order  


## Output Format  

Return the merged price list in non-decreasing order.


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
