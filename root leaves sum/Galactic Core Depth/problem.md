## Title

Galactic Core Depth

## Slug

galactic-core-depth

## Difficulty

Medium

## Description

Across the cosmos, energy flows through a massive `Galactic Energy Tree`.  
Each node represents a stellar core.  
Determine the `sum of energies of the deepest stars` — those at the farthest ends of the galactic network.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Deepest stars `[7, 8]` yield total energy `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Deep stars `[9, 1, 4, 5]` total `19`.

## Input Format  

- First line: integer `n`  
- Second line: `n` space-separated values in level order

## Output Format  

- Return the total stellar energy from deepest stars.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, dfs
