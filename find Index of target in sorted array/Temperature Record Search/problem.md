## Title

Temperature Record Search

## Slug

temperature-record-search

## Difficulty

Easy

## Description

Meteorological sensors record temperatures in `non-decreasing order`.  
Given the array `temps`, find if the reading `k` exists.  

Return its `index` if found, otherwise `-1`.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

6  
10 15 20 25 30 35  
30

#### Output

4

#### Explanation

Temperature 30 is found at index 4.

### 2

#### Input

6  
5 10 15 20 25 30  
9

#### Output

-1

#### Explanation

No temperature reading equals 9.

## Input Format  

- First line: sorted array `temps[]`.  
- Second line: integer `k` — target temperature.

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
