## Title

Echo Tree Depth

## Slug

echo-tree-depth

## Difficulty

Medium

## Description

Sound travels through the `Tree of Echoes`, where every node amplifies a frequency.  
Your mission is to calculate the `sum of sound amplitudes` from the `deepest echoes` in this acoustic network.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Deepest echoes `[7, 8]` have amplitude `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Echoes `[9, 1, 4, 5]` total `19`.

## Input Format  

- First line: integer `n` — number of echo nodes  
- Second line: level-order traversal (`null` for missing)

## Output Format  

- Return the `sum of deepest echo amplitudes`.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, traversal
