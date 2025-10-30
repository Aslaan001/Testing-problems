## Title

Crystal Power Depth

## Slug

crystal-power-depth

## Difficulty

Medium

## Description

In the caverns of Aldor, glowing crystals form a `Tree of Power`.  
Each crystal node contains a unit of magical charge.  
Calculate the `sum of charges` held by the `deepest crystals` within the cave network.

## Examples

### 1

#### Input

13
1 2 3 4 5 null 6 7 null null null null 8

#### Output

15

#### Explanation

Deep crystals `[7, 8]` shine with power `15`.

### 2

#### Input

15
6 7 8 2 7 1 3 9 null 1 4 null null null 5

#### Output

19

#### Explanation

Crystals `[9, 1, 4, 5]` contain power `19`.

## Input Format  

- First line: integer `n` — number of crystal nodes  
- Second line: `n` space-separated level-order values (`null` for missing)

## Output Format  

- Return the `sum of charges in the deepest crystals`.

## Constraints  

- 2 ≤ n ≤ 1e5  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-tree, recursion
