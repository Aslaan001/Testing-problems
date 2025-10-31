## Title

Treasure Map Coordinate Insert

## Slug

treasure-map-coordinate-insert

## Difficulty

Medium

## Description

An explorer keeps a list of coordinates (x-values) sorted in ascending order on a treasure map.  
After discovering a new coordinate, find the correct position to insert it so the list remains sorted.

Use `binary search` for efficiency.

Return the `0-based index` where it should be inserted.

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

- First line: two integers `n` and `key`.  
- Second line: `n` sorted coordinates.

## Output Format  

- Integer — insertion index.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
