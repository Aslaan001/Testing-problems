## Title
Organize Magic Chain

## Slug
organize-magic-chain

## Difficulty
Medium

## Description

You are given the `head` of a magical chain of power stones, each with an energy level represented by an integer.  
Your task is to sort these stones in ascending order of their energy and return the `head` of the sorted chain.

## Examples

### 1

#### Input
4
4 2 1 3

#### Output
1 2 3 4

#### Explanation
The chain `4 -> 2 -> 1 -> 3` becomes `1 -> 2 -> 3 -> 4` after sorting.

### 2

#### Input
5
-1 5 3 4 0

#### Output
-1 0 3 4 5

#### Explanation
Energy stones are rearranged in increasing order of power.

## Input Format
-   First line: integer `n` — number of stones in the chain.  
-   Second line: `n` integers representing the energy values.

## Output Format
Print the sorted chain of stone energies separated by a space.

## Constraints
0 <= n <= 50000  
-100000 <= node.val <= 100000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sorting, two-pointers, merge-sort
