## Title
Top View of the Arc Metal Dunes

## Slug
top-view-of-the-arc-metal-dunes

## Difficulty
Medium

## Description
In the world of arc metal dunes, formations stretch across the land in strange, layered patterns. When viewed from above, only the formations not directly overshadowed by others remain visible. Your mission is to determine this topmost outline, moving from the leftmost visible point to the rightmost. The structure is represented as a level‑order array, where 'N' marks missing segments.

## Examples

### 1
#### Input
[1, 2, 3, N, 4, 5, 6]

#### Output
2 1 3 6

#### Explanation

From the left side, 2 is visible.

The root 1 is visible.

From the right side, 3 is visible.

Nodes 4 → 5 → 6 lie vertically aligned, but only the lowest 6 is visible.

### 2
#### Input
[7, 3, 9, 2, 5, 8, 12, N, N, 4, 6]

#### Output
2 3 7 9 12

#### Explanation

From the far left, 2 is visible.

Then 3 and root 7.

On the right, 9 and 12 are visible.

Nodes 5, 8, 4, 6 are hidden under others in the same vertical line.

### 3
#### Input
[10, 20, 30, 40, N, N, 60, N, N, N, N, 50]

#### Output
40 20 10 30 60

#### Explanation

From the leftmost side, 40 is visible.

Then 20 and the root 10.

On the right, 30 and 60 are visible.

Node 50 lies directly under 20, hence hidden.

## Input Format

The tree is provided as an array in level-order traversal.

"N" (or "null") denotes a missing child.

Example:

[7, 3, 9, 2, 5, 8, 12, N, N, 4, 6]

## Output Format

Return the top view of the binary tree as space-separated integers, from leftmost to rightmost.

## Constraints

1 ≤ number of nodes ≤ 10^5

1 ≤ node values ≤ 10^5

Input represents a valid binary tree

## Time Limit

1 second

## Memory Limit

256 MB

## Tags

binary-tree, bfs, hashmap
