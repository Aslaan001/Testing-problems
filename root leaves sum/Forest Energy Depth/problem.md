## Title

Forest Energy Depth

## Slug

forest-energy-depth

## Difficulty

Medium

## Description

In the enchanted forest of Viridara, every root and branch glows with the life energy of nature.  
Each node in the `Tree of Life` represents a pulse of energy.  
Your quest is to find the **sum of energies of the deepest roots**, where the oldest spirits reside.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

The deepest roots `[7, 8]` sum to `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

The deepest roots `[9, 1, 4, 5]` total to `19`.

## Input Format  

- First line: integer `n` — number of nodes  
- Second line: `n` space-separated values (level-order, `null` for missing nodes)

## Output Format  

- Return the sum of values at the deepest level.

## Constraints  

- 2 ≤ n ≤ 1e5  
- Node values are integers.

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, bfs, recursion
