## Title

Root Memory Depth

## Slug

root-memory-depth

## Difficulty

Medium

## Description

In a digital archive, memories are stored in a binary `Memory Tree`.  
Each node holds data capacity.  
Find the `sum of data` in the `deepest memory leaves`.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Deepest memories `[7, 8]` store total data `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Memory nodes `[9, 1, 4, 5]` sum to `19`.

## Input Format  

- First line: integer `n`  
- Second line: `n` space-separated values (`null` for missing)

## Output Format  

- Return the `sum of data at the deepest memory nodes`.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, bfs
