## Title

Robot Chip Finder

## Slug

robot-chip-finder

## Difficulty

Easy

## Description

A factory stores `robot chips` sorted by their `version IDs` in `non-decreasing order`.  
You must locate the chip with ID `k`.  

If present, return its `index`; if not, return `-1`.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

5  
11 22 33 44 55  
33

#### Output

2

#### Explanation

Chip ID 33 lies at index 2.

### 2

#### Input

5  
2 4 6 8 10  
9

#### Output

-1

#### Explanation

No chip has ID 9.

## Input Format  

- First line: sorted array `chips[]`.  
- Second line: integer `k` — target ID.

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
