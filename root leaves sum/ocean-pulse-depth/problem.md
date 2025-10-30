## Title

Ocean Pulse Depth

## Slug

ocean-pulse-depth

## Difficulty

Medium

## Description

In the endless sea, waves connect through a hidden `Pulse Tree`.  
Each node carries the rhythm of the tides.  
Your task is to find the `sum of pulse values` of the `deepest ocean waves`, where the heartbeat of the sea is strongest.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Deepest waves `[7, 8]` have combined pulse `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Deep waves `[9, 1, 4, 5]` total `19`.

## Input Format  

- First line: integer `n` — number of nodes in the wave network  
- Second line: `n` space-separated values representing level-order traversal (`null` for missing nodes)

## Output Format  

- Output the `sum of pulse values from deepest waves`.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, bfs, recursion
