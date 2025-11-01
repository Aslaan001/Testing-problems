## Title
Arrange Train Cars

## Slug
arrange-train-cars

## Difficulty
Medium

## Description

Each train car has a number showing its load weight.  
You are given a linked list representing the cars in random order.  
Rearrange the cars so that their weights appear in ascending order and return the sorted list.

## Examples

### 1

#### Input
4
4 2 1 3

#### Output
1 2 3 4

#### Explanation
Cars with weights `4 -> 2 -> 1 -> 3` become `1 -> 2 -> 3 -> 4`.

### 2

#### Input
5
-1 5 3 4 0

#### Output
-1 0 3 4 5

#### Explanation
Train cars are organized by increasing weight.

## Input Format
- First line: integer `n`.  
- Second line: `n` integers — car weights.

## Output Format
Sorted list of car weights separated by spaces.

## Constraints
0 <= n <= 50000  
-100000 <= node.val <= 100000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sorting, merge-sort
