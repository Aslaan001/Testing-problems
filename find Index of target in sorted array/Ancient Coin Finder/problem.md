## Title

Ancient Coin Finder

## Slug

ancient-coin-finder

## Difficulty

Easy

## Description

In the vault of `Numir`, coins are sorted by their `mint value` in `non-decreasing order`.  
You must locate the coin with value `k`.  

Return its `index` if found, otherwise `-1`.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

5  
5 10 20 40 60  
20

#### Output

2

#### Explanation

Coin with value 20 lies at index 2.

### 2

#### Input

5  
3 6 9 12 15  
8

#### Output

-1

#### Explanation

Coin 8 not found in vault.

## Input Format  

- First line: sorted array `coins[]`.  
- Second line: integer `k` — coin value.

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
