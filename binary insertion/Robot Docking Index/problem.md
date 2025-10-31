## Title

Robot Docking Index

## Slug

robot-docking-index

## Difficulty

Medium

## Description

In a futuristic hangar, robots dock in ascending order based on their energy ID.  
A new robot arrives — find where it should dock so that the order remains correct.

Use `binary search` to locate the index.

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
- Second line: sorted energy IDs.

## Output Format  

- Integer — docking index.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  
- Array is sorted ascendingly.  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
