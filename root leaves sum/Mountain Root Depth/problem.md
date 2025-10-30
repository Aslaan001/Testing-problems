## Title

Mountain Root Depth

## Slug

mountain-root-depth

## Difficulty

Medium

## Description

At the base of the Great Titan Peaks lies an ancient `Root Tree` that channels the spirit of the mountains.  
Each root carries the power of the earth.  
Find the `sum of strengths` from the `deepest roots` buried beneath the mountain’s surface.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Deepest roots `[7, 8]` together have power `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Roots `[9, 1, 4, 5]` sum to `19`.

## Input Format  

- First line: integer `n` — number of root nodes  
- Second line: level-order traversal (`null` for missing)

## Output Format  

- Return the `sum of deepest roots`.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, bfs
