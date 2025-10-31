## Title

Galactic Data Insert

## Slug

galactic-data-insert

## Difficulty

Medium

## Description

In the Galactic Data Registry, planet IDs are sorted by discovery order.  
When a new planet is discovered, you must insert its ID at the correct position so that the registry remains sorted.

Find the position using `binary search`.

Return the `0-based index` where the new planet ID should be inserted.

## Examples

### 1

#### Input

5 4
1 3 5 6 8

#### Output
2

### 2

#### Input

4 1
2 4 6 8 

#### Output
0

## Input Format  

- First line: integers `n` and `key`.  
- Second line: sorted planet IDs.

## Output Format  

- A single integer — insertion index.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  
- IDs are sorted in ascending order.  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
