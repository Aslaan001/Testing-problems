## Title

Spirit Root Depth

## Slug

spirit-root-depth

## Difficulty

Medium

## Description

In the ethereal realm, souls grow through the `Tree of Renewal`.  
Each spirit node glows with essence energy.  
Find the `sum of glows` of the `deepest spirits` in the afterworld’s tree.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Deepest spirits `[7, 8]` shine with total essence `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Spirits `[9, 1, 4, 5]` glow with energy `19`.

## Input Format  

- First line: integer `n`  
- Second line: `n` space-separated level-order values (`null` for missing)

## Output Format  

- Output the `sum of deepest spirit glows`.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, dfs
