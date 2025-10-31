## Title

Treasure Index

## Slug

treasure-index

## Difficulty

Easy

## Description

On the `Golden Shore`, treasures are buried in order of their `value points`.  
The treasure values are stored in an array `treasures` in `non-decreasing order`.  

You need to find the treasure with value `k`.  

If it exists, return its `index`. If not, return `-1`.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

5  
10 15 20 25 30  
20

#### Output

2

#### Explanation

The treasure with value 20 is located at index 2.

### 2

#### Input

5  
5 9 11 14 18  
7

#### Output

-1

#### Explanation

No treasure with value 7 exists.

## Input Format  

- First line: sorted array `treasures[]`.  
- Second line: integer `k` — the treasure value.

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
