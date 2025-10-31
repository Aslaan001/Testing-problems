## Title

Ancient Scroll Index

## Slug

ancient-scroll-index

## Difficulty

Easy

## Description

In the archives of `Nemorium`, ancient scrolls are arranged in `non-decreasing order` of their `seal numbers`.  
You must find the scroll with seal number `k` from the array `scrolls`.  

If found, return its `index`; if not, return `-1`.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

5  
1 3 5 7 9  
5

#### Output

2

#### Explanation

The scroll with seal 5 lies at index 2.

### 2

#### Input

5  
10 20 30 40 50  
25

#### Output

-1

#### Explanation

Scroll with seal 25 is not in the archive.

## Input Format  

- First line: sorted array `scrolls[]`.  
- Second line: integer `k` — the seal number to locate.

## Output Format  

Return the `index` if found, else `-1`.

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
