## Title

Planetary Orbit Insert

## Slug

planetary-orbit-insert

## Difficulty

Medium

## Description

Astronomers catalog planets in a sorted list based on their orbital radius (in million km).  
A newly found planet must be inserted into the list at the correct position so that the catalog remains sorted.

Find the insertion index using `binary search`.

Return the `0-based index`.

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
- Second line: `n` integers representing orbital radii.

## Output Format  

- Integer — insertion index for the new planet.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
