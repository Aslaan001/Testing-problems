## Title

Volcanic Vein Depth

## Slug

volcanic-vein-depth

## Difficulty

Medium

## Description

Deep inside a volcano, molten channels form a `Vein Network` of fiery flow.  
Each node represents a chamber’s lava pressure.  
Compute the `sum of pressures` from the `deepest lava chambers`.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Deepest chambers `[7, 8]` hold total pressure `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Lava chambers `[9, 1, 4, 5]` sum to `19`.

## Input Format  

- First line: integer `n` — number of chambers  
- Second line: `n` space-separated values (`null` for missing)

## Output Format  

- Output the `sum of pressures from deepest chambers`.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, bfs
