## Title

Merge Expenses

## Slug

merge-expenses

## Difficulty


## Description

You are managing budgets for two departments. Each department records expenses in sorted order, represented as arrays `nums1` and `nums2`.  

Your task is to merge both expense lists into one unified report.




## Examples

### 1

#### Input

3
100 200 400
3
150 300 450

#### Output

100 150 200 300 400 450

#### Explanation

After merging, the combined expense list is [100,150,200,300,400,450].


### 2

#### Input

1
500
0

#### Output

500

#### Explanation

Only one department has expenses, so the merged list remains [500].


## Input Format  

- First line: integer `n` — number of expenses in the first list (`nums1`)  
- Second line: `n` integers — expenses in non-decreasing order  
- Third line: integer `m` — number of expenses in the second list (`nums2`)  
- Fourth line: `m` integers — expenses in non-decreasing order  


## Output Format  

Return the merged list of expenses in non-decreasing order.


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
