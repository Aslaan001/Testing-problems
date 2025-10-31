## Title

Sorted Log Entry

## Slug

sorted-log-entry

## Difficulty

Medium

## Description

A data center maintains log entries sorted by their timestamp IDs.  
You receive a new log and must determine where to insert it so the sequence remains ordered.

Use `binary search` to find the position efficiently.

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

- Line 1: integers `n` and `key`.  
- Line 2: sorted log timestamps.

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
