## Title

Merge Patients

## Slug

merge-patients

## Difficulty


## Description

You are a hospital administrator merging patient ID lists from two branches. Each list is sorted and represented by integer arrays `nums1` and `nums2`.  

Your task is to merge both branches’ records into one master list in ascending order.




## Examples

### 1

#### Input

3
101 104 107
3
102 105 108

#### Output

101 102 104 105 107 108

#### Explanation

After merging both branches’ lists, the master record becomes [101,102,104,105,107,108].


### 2

#### Input

2
110 115
0

#### Output

110 115

#### Explanation

Only one branch has records, so the merged list remains [110,115].


## Input Format  

- First line: integer `n` — number of patients in the first list (`nums1`)  
- Second line: `n` integers — IDs in non-decreasing order  
- Third line: integer `m` — number of patients in the second list (`nums2`)  
- Fourth line: `m` integers — IDs in non-decreasing order  


## Output Format  

Return the merged patient list in non-decreasing order.


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
