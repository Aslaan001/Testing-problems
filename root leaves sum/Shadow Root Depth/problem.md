## Title

Shadow Root Depth

## Slug

shadow-root-depth

## Difficulty

Medium

## Description

In the land of dusk, there exists a dark `Shadow Tree` that binds light and void.  
Each node carries a trace of shadow energy.  
You must determine the `sum of shadow energies` from the `deepest roots` hidden beneath the veil.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

The deepest roots `[7, 8]` contain total energy `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Roots `[9, 1, 4, 5]` hold energy `19`.

## Input Format  

- First line: integer `n` — number of shadow nodes  
- Second line: level-order traversal (`null` for missing)

## Output Format  

- Output the `sum of energies of the deepest roots`.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, bfs
