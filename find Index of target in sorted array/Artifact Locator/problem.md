## Title

Artifact Locator

## Slug

artifact-locator

## Difficulty

Easy

## Description

In the ruins of `Eldoria`, ancient artifacts are arranged by their `energy levels` in `non-decreasing order` inside an archive list called `artifacts`.  

You, the `Archaeon`, must find the artifact whose energy value equals `k`.  

If it exists, return its `index`.  
Otherwise, return `-1`.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

5  
2 5 8 12 20  
12

#### Output

3

#### Explanation

The artifact with energy 12 is located at index 3.

### 2

#### Input

5  
1 3 6 8 10  
4

#### Output

-1

#### Explanation

No artifact has energy 4, so return -1.

## Input Format  

- First line: sorted array `artifacts[]`.  
- Second line: integer `k` — the energy value to search.

## Output Format  

Return `index` of artifact if found, otherwise `-1`.

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
