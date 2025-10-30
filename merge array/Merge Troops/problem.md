## Title

Merge Troops

## Slug

merge-troops

## Difficulty


## Description

You are a commander organizing two battalions for a parade. Each battalion’s soldiers are arranged by height in non-decreasing order, represented as arrays `nums1` and `nums2`.  

Your task is to merge both battalions into a single parade line, sorted by height.




## Examples

### 1

#### Input

3
160 165 170
3
162 168 175

#### Output

160 162 165 168 170 175

#### Explanation

After merging, the heights are arranged as [160,162,165,168,170,175].


### 2

#### Input

1
180
0

#### Output

180

#### Explanation

The second battalion has no soldiers, so the merged line is [180].


## Input Format  

- First line: integer `n` — number of soldiers in battalion one (`nums1`)  
- Second line: `n` integers — heights in non-decreasing order  
- Third line: integer `m` — number of soldiers in battalion two (`nums2`)  
- Fourth line: `m` integers — heights in non-decreasing order  


## Output Format  

Return the merged parade line of soldiers in non-decreasing order.


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
