## Title
Sort Animal Ages

## Slug
sort-animal-ages

## Difficulty
Medium

## Description

A zookeeper maintains a record of animal ages in a linked list.  
The records are not sorted.  
Your task is to sort the ages in ascending order and return the `head` of the sorted list.

## Examples

### 1

#### Input
4
4 2 1 3

#### Output
1 2 3 4

#### Explanation
Animal ages are arranged from youngest to oldest.

### 2

#### Input
5
-1 5 3 4 0

#### Output
-1 0 3 4 5

#### Explanation
The list is now sorted in increasing age order.

## Input Format
- First line: integer `n`.  
- Second line: `n` integers representing ages.

## Output Format
Sorted animal ages printed in ascending order.

## Constraints
0 <= n <= 50000  
-100000 <= node.val <= 100000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sorting, merge-sort
