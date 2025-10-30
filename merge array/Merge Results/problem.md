## Title

Merge Results

## Slug

merge-results

## Difficulty


## Description

You are a scientist merging sorted experimental results from two trials. Each trial’s measurements are stored in arrays `nums1` and `nums2`.  

Your task is to merge both result lists into one ordered dataset.




## Examples

### 1

#### Input

3
5 7 9
3
6 8 10

#### Output

5 6 7 8 9 10

#### Explanation

After merging, the combined dataset is [5,6,7,8,9,10].


### 2

#### Input

1
11
0

#### Output

11

#### Explanation

Only one trial’s data exists, so the merged list remains unchanged.


## Input Format  

- First line: integer `n` — number of results in the first trial (`nums1`)  
- Second line: `n` integers — results in non-decreasing order  
- Third line: integer `m` — number of results in the second trial (`nums2`)  
- Fourth line: `m` integers — results in non-decreasing order  


## Output Format  

Return the merged experimental results in non-decreasing order.


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
