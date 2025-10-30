## Title

Coral Light Depth

## Slug

coral-light-depth

## Difficulty

Medium

## Description

Beneath the ocean lies a vast reef called the `Coral Nexus`.  
Each coral node radiates light energy, and deeper corals glow brighter.  
Find the `total light energy` from the `deepest coral tips` of this mystical structure.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Deepest corals `[7, 8]` emit light totaling `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Deep corals `[9, 1, 4, 5]` glow with energy `19`.

## Input Format  

- First line: integer `n`  
- Second line: level-order traversal with `null` for empty nodes

## Output Format  

- Print the total light energy at the deepest corals.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, level-order
