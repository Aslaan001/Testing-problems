## Title

Rune Energy Search

## Slug

rune-energy-search

## Difficulty

Easy

## Description

In the magical realm of `Runeria`, energy runes are arranged in a sorted order by their `energy values`.  
You must determine if a rune with energy `k` exists in the array `runes`.  

Return its `index` if it exists, or `-1` otherwise.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

6  
3 5 7 9 11 13  
9

#### Output

3

#### Explanation

Rune with energy 9 lies at index 3.

### 2

#### Input

6  
2 4 6 8 10 12  
1

#### Output

-1

#### Explanation

No rune has energy value 1.

## Input Format  

- First line: sorted array `runes[]`.  
- Second line: integer `k` — target energy.

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
