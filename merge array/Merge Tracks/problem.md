## Title

Merge Tracks

## Slug

merge-tracks

## Difficulty


## Description

You are a DJ combining two playlists, each sorted by track duration. Both playlists are given as integer arrays `nums1` and `nums2`.  

Your task is to merge them into one continuous playlist sorted by duration.




## Examples

### 1

#### Input

3
120 150 180
3
100 160 200

#### Output

100 120 150 160 180 200

#### Explanation

After merging both playlists, the final playlist durations are [100,120,150,160,180,200].


### 2

#### Input

1
90
0

#### Output

90

#### Explanation

The second playlist is empty, so the final playlist remains the same.


## Input Format  

- First line: integer `n` — number of tracks in the first playlist (`nums1`)  
- Second line: `n` integers — track durations in non-decreasing order  
- Third line: integer `m` — number of tracks in the second playlist (`nums2`)  
- Fourth line: `m` integers — track durations in non-decreasing order  


## Output Format  

Return the merged playlist in non-decreasing order of duration.


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
