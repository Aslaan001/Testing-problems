## Title
Frozen Observatory Guards

## Slug
frozen-observatory-guards

## Difficulty
Medium

## Description
In the frozen observatory, a hierarchy of guards forms a structured BST-like order. Each guard holds a unique identifier. When a specific one must be removed, it must be removed while preserving the exact BST order. If it has two linked successors, the smallest in its right branch replaces it. With one successor, that successor takes its place; with none, it vanishes. If it does not exist, nothing changes.

## Examples

### 1
#### Input
img(https://d3gmywgj71m21w.cloudfront.net/coding-questions/44a1e3055f1debb000894e97c01dcb44)

root = [12,7,18,5,10,15,20], key = 18


#### Output
[12,7,20,5,10,15]

#### Explanation

The guardian with power 18 is deleted. It is replaced by its in-order successor, which is the smallest guardian in its right subtree — 20 in this case.

img(https://d3gmywgj71m21w.cloudfront.net/coding-questions/70af5aab44e48fa3c0c57eb3f3e0f978)

### 2
#### Input
img(https://d3gmywgj71m21w.cloudfront.net/coding-questions/281cb2e41d5fc75a2caf7300ae4d4128)

root = [10,5,15,3,7,12,17], key = 5

#### Output
[10,7,15,3,null,12,17]

#### Explanation

The guardian with power 5 is deleted. Since it has two children, it is replaced by its in-order successor — the smallest node in its right subtree, which is 7. This maintains the BST properties.

img(https://d3gmywgj71m21w.cloudfront.net/coding-questions/cd4a6fa52f401ce45c568a7c2526de5e)

### 3
#### Input
root = [], key = 2

#### Output
[]

#### Explanation

The BST is empty. No deletion is required.

## Input Format

- root: array representing a valid binary search tree (may be empty).

- key: integer representing the guardian to delete.

## Output Format

Return the root node of BST after updation.

## Constraints

- Number of nodes in the tree: 0 ≤ n ≤ 10^4
- Node values: -10^5 ≤ Node.val ≤ 10^5
- All node values are unique.
- Input tree is a valid BST.
- Key value: -10^5 ≤ key ≤ 10^5

## Time Limit
1 second

## Memory Limit
256 MB

## Tags
Binary Tree, Binary Search Tree, Recursion, Tree Manipulation
