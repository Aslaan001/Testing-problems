## Title

Code Fragment Search

## Slug

code-fragment-search

## Difficulty

Easy

## Description

Inside the `CyberVault`, encrypted code fragments are stored in `non-decreasing order`.  
Find whether a fragment with ID `k` exists.  

Return its `index` if found, otherwise `-1`.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

5  
1 3 5 7 9  
7

#### Output

3

#### Explanation

Code fragment 7 is at index 3.

### 2

#### Input

5  
2 4 6 8 10  
11

#### Output

-1

#### Explanation

No fragment with ID 11.

## Input Format  

- First line: sorted array `fragments[]`.  
- Second line: integer `k` — target ID.

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
