## Title

Star Registry Search

## Slug

star-registry-search

## Difficulty

Easy

## Description

In the `Galactic Registry`, stars are cataloged by their `brightness levels` in `non-decreasing order`.  
Your task is to find a star with brightness value `k` in the array `stars`.  

If the star exists, return its `index`. Otherwise, return `-1`.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

5  
2 4 6 8 10  
8

#### Output

3

#### Explanation

The star with brightness 8 is located at index 3.

### 2

#### Input

5  
5 9 12 15 20  
7

#### Output

-1

#### Explanation

No star with brightness 7 exists in the registry.

## Input Format  

- First line: sorted array `stars[]`.  
- Second line: integer `k` — brightness level to find.

## Output Format  

Return `index` if found, otherwise `-1`.

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
