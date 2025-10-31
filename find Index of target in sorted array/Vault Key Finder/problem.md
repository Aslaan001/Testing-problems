## Title

Galaxy Coordinate Finder

## Slug

galaxy-coordinate-finder

## Difficulty

Easy

## Description

In the `AstroNet` database, galaxy coordinates are stored in a `non-decreasing order` array called `coords`.  
You need to find the coordinate that matches `k`.  

Return its `index` if found, otherwise `-1`.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

5  
2 6 9 13 15  
13

#### Output

3

#### Explanation

Coordinate 13 lies at index 3.

### 2

#### Input

5  
1 3 5 7 9  
8

#### Output

-1

#### Explanation

No galaxy coordinate matches 8.

## Input Format  

- First line: sorted array `coords[]`.  
- Second line: integer `k` — target coordinate.

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
