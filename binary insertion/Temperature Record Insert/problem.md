## Title

Temperature Record Insert

## Slug

temperature-record-insert

## Difficulty

Medium

## Description

Meteorologists maintain a sorted list of recorded temperatures.  
Given a new temperature value, determine where it should be inserted to maintain order.

Use `binary search` to find the correct index.

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

- First line: integers `n` and `key`.  
- Second line: sorted temperatures.

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
