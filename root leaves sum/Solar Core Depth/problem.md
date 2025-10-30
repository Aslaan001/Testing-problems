## Title

Solar Core Depth

## Slug

solar-core-depth

## Difficulty

Medium

## Description

Within a massive star, nuclear cores are connected in a radiant `Solar Tree`.  
Each node represents a fusion core's heat value.  
Find the `sum of heat values` from the `deepest cores`, buried within the blazing star.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Deep cores `[7, 8]` produce total heat `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Deepest cores `[9, 1, 4, 5]` emit heat `19`.

## Input Format  

- First line: integer `n` — number of cores  
- Second line: `n` space-separated values (`null` for missing)

## Output Format  

- Output the `sum of heat from deepest cores`.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, bfs
