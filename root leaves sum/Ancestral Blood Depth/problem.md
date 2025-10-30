## Title

Ancestral Blood Depth

## Slug

ancestral-blood-depth

## Difficulty

Medium

## Description

In the empire of Atheron, bloodlines trace back to ancient rulers.  
Each node in the `Ancestral Tree` represents a descendant’s strength.  
Your goal is to compute the `sum of powers` of the deepest generation of this royal lineage.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Youngest heirs `[7, 8]` have total power `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Heirs `[9, 1, 4, 5]` sum to `19`.

## Input Format  

- First line: integer `n` — number of members  
- Second line: level-order traversal (`null` for missing)

## Output Format  

- Return the `sum of deepest heirs' strengths`.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, bfs
