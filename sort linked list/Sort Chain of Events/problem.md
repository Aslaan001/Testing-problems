## Title
Sort Chain of Events

## Slug
sort-chain-of-events

## Difficulty
Medium

## Description

An event recorder logs events with numerical priorities in a linked list.  
Sort the events in ascending order of priority.

## Examples

### 1

#### Input
4
4 2 1 3

#### Output
1 2 3 4

#### Explanation
Events are ordered from lowest to highest priority.

### 2

#### Input
5
-1 5 3 4 0

#### Output
-1 0 3 4 5

#### Explanation
All event priorities are now sorted correctly.

## Input Format
- First line: integer `n`.  
- Second line: event priorities.

## Output Format
Sorted priorities.

## Constraints
0 <= n <= 50000  
-100000 <= node.val <= 100000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sorting, merge-sort
