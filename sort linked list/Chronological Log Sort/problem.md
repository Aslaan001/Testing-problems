## Title
Chronological Log Sort

## Slug
chronological-log-sort

## Difficulty
Medium

## Description

A data logger records events in an unsorted linked list of timestamps.  
Sort the list so that events appear in chronological (ascending) order.

## Examples

### 1

#### Input
4
4 2 1 3

#### Output
1 2 3 4

#### Explanation
Logs are sorted chronologically.

### 2

#### Input
5
-1 5 3 4 0

#### Output
-1 0 3 4 5

#### Explanation
Timestamps are sorted in ascending order.

## Input Format
- Line 1: integer `n`.  
- Line 2: timestamps.

## Output Format
Chronologically sorted timestamps.

## Constraints
0 <= n <= 50000  
-100000 <= node.val <= 100000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sorting, merge-sort
