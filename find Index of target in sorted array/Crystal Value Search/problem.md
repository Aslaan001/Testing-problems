## Title

Crystal Value Search

## Slug

crystal-value-search

## Difficulty

Easy

## Description

Crystals from the mines of `Solara` are arranged in ascending order based on their `purity value`.  
Find if a crystal with value `k` exists.  

Return its `index` if present, or `-1` otherwise.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

6  
2 4 6 8 10 12  
6

#### Output

2

#### Explanation

Crystal 6 is located at index 2.

### 2

#### Input

6  
3 5 7 9 11 13  
4

#### Output

-1

#### Explanation

Crystal 4 does not exist.

## Input Format  

- First line: sorted array `crystals[]`.  
- Second line: integer `k` — target value.

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
