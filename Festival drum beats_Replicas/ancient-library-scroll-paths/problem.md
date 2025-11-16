## Title
Ancient Library Scroll Paths

## Slug
ancient-library-scroll-paths

## Difficulty
Medium

## Description
In a vast ancient library, shelves form layered aisles filled with scrolls. Scholars traverse each aisle alternating directions: the first from east to west, the next from west to east, continuing this pattern throughout. The shelves follow a branching layout similar to a binary tree. Your task is to determine the exact sequence in which the scrolls are inspected across the aisles, following this alternating traversal pattern.

## Examples

### 1
#### Input
[8,4,12,2,null,10,null]

#### Output
[[8],[12,4],[2,10]]

#### Explanation

Row 1: [8]

Row 2: [12, 4] (right to left)

Row 3: [2, 10] (left to right, skipping nulls)

### 2
#### Input
[10,5,15,3,7,12,18]

#### Output
[[10],[15,5],[3,7,12,18]]

#### Explanation

Row 1: [10]

Row 2: [15, 5] (right to left)

Row 3: [3, 7, 12, 18] (left to right)

### 3
#### Input
[]

#### Output
[]

## Input Format

A binary tree is given in array form (level-order), where null represents the absence of a node.

Example: [8,4,12,2,null,10,null] represents the tree:

Root = 8

Left child of 8 = 4, Right child of 8 = 12

Left child of 4 = 2, Right child of 4 = null

Left child of 12 = 10, Right child of 12 = null

## Output Format

A list of lists, where each inner list contains the node values of a row, traversed in zigzag order.

## Constraints

- The number of nodes in the tree is in the range [0, 2000].
- -100 ≤ Node.val ≤ 100

## Time Limit
1 second

## Memory Limit
256 MB

## Tags
binary-tree, bfs
