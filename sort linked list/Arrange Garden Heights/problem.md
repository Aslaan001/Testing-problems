## Title
Arrange Garden Heights

## Slug
arrange-garden-heights

## Difficulty
Medium

## Description

You are organizing a magical garden where each flower has a different height.  
The heights are stored in a linked list in random order.  
Rearrange them so that the garden blooms in perfect ascending height order and return the `head` of the sorted list.

## Examples

### 1

#### Input
4
4 2 1 3

#### Output
1 2 3 4

#### Explanation
Flower heights `4 -> 2 -> 1 -> 3` become `1 -> 2 -> 3 -> 4` after sorting.

### 2

#### Input
5
-1 5 3 4 0

#### Output
-1 0 3 4 5

#### Explanation
Flowers are arranged in increasing order of height.

## Input Format
- First line: integer `n` — number of flowers.  
- Second line: `n` integers representing the heights.

## Output Format
Print the heights in sorted ascending order.

## Constraint
