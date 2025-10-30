## Title

Temple Spirit Depth

## Slug

temple-spirit-depth

## Difficulty

Medium

## Description

In a forgotten temple, sacred spirits are bound to a `Tree of Devotion`.  
Each node radiates divine energy.  
Find the `sum of energies` of the `deepest spirits` in the tree’s roots.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Deepest spirits `[7, 8]` give total devotion `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Deepest spirits `[9, 1, 4, 5]` total `19`.

## Input Format  

- First line: integer `n` — number of nodes  
- Second line: level-order traversal (`null` for missing)

## Output Format  

- Return the `sum of deepest spirit energies`.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, bfs
