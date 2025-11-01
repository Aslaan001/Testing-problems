## Title
Sort Player Scores

## Slug
sort-player-scores

## Difficulty
Medium

## Description

You are building a scoreboard system where player scores are stored in a linked list.  
Sort the scores in ascending order and return the `head` of the sorted list.

## Examples

### 1

#### Input
4
4 2 1 3

#### Output
1 2 3 4

#### Explanation
Scores become ordered from lowest to highest.

### 2

#### Input
5
-1 5 3 4 0

#### Output
-1 0 3 4 5

#### Explanation
The sorted scoreboard is displayed.

## Input Format
- First line: integer `n`.  
- Second line: `n` integers — player scores.

## Output Format
Sorted scores separated by spaces.

## Constraints
0 <= n <= 50000  
-100000 <= node.val <= 100000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sorting, merge-sort
