## Title

Lunar Energy Depth

## Slug

lunar-energy-depth

## Difficulty

Medium

## Description

The Moon of Veralis contains an ancient network of `Lunar Nodes`.  
Each node holds the energy of moonlight.  
Your task is to find the `sum of moonlight energies` from the `deepest lunar nodes`.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Deepest nodes `[7, 8]` have energy `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Lunar nodes `[9, 1, 4, 5]` emit total energy `19`.

## Input Format  

- First line: integer `n`  
- Second line: `n` space-separated values (`null` for missing)

## Output Format  

- Return the `sum of deepest lunar energies`.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, recursion
