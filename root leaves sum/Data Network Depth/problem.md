## Title

Data Network Depth

## Slug

data-network-depth

## Difficulty

Medium

## Description

A futuristic data system is modeled as a binary `Network Tree`.  
Each node transmits a data strength value.  
Your task is to compute the `sum of data strengths` at the `deepest terminals` in the network.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Deepest terminals `[7, 8]` total to `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Terminals `[9, 1, 4, 5]` add up to `19`.

## Input Format  

- First line: integer `n` — number of nodes  
- Second line: `n` space-separated values (use `null` for missing)

## Output Format  

- Return the `sum of deepest data nodes`.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, bfs
