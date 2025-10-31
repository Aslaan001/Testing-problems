## Title

Frequency Search

## Slug

frequency-search

## Difficulty

Easy

## Description

A scientist records frequencies of sound waves in `non-decreasing order` inside an array called `frequencies`.  
Find whether a wave with frequency `k` exists.  

Return its `index` if found, otherwise `-1`.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

6  
5 10 15 20 25 30  
25

#### Output

4

#### Explanation

Frequency 25 is found at index 4.

### 2

#### Input

6  
2 4 6 8 10 12  
3

#### Output

-1

#### Explanation

Frequency 3 does not exist.

## Input Format  

- First line: sorted array `frequencies[]`.  
- Second line: integer `k` — target frequency.

## Output Format  

Return `index` if found, else `-1`.

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
