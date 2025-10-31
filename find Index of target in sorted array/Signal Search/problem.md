## Title

Signal Search

## Slug

signal-search

## Difficulty

Easy

## Description

In the `Data Constellation`, a sequence of `signal strengths` is stored in `non-decreasing order` in an array called `signals`.  

Find whether the signal with strength `k` exists.  

If it does, return its `index`. Otherwise, return `-1`.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

6  
2 4 6 8 10 12  
8

#### Output

3

#### Explanation

Signal 8 is found at index 3.

### 2

#### Input

6  
1 3 5 7 9 11  
2

#### Output

-1

#### Explanation

Signal 2 does not exist.

## Input Format  

- First line: sorted array `signals[]`.  
- Second line: integer `k` — target signal.

## Output Format  

Return index if found, else `-1`.

## Constraints  

- 1 ≤ n ≤ 1e4  
- 1 ≤ arr[i] ≤ 1e9  
- 0 ≤ k ≤ 1e9  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-search, arrays.
