## Title
Sort Music Notes

## Slug
sort-music-notes

## Difficulty
Medium

## Description

A composer’s notes are represented as a linked list of integer pitches.  
Sort the list so that the notes appear in ascending order by pitch and return the new head of the list.

## Examples

### 1

#### Input
4
4 2 1 3

#### Output
1 2 3 4

#### Explanation
Notes are rearranged from `4 -> 2 -> 1 -> 3` to `1 -> 2 -> 3 -> 4`.

### 2

#### Input
5
-1 5 3 4 0

#### Output
-1 0 3 4 5

#### Explanation
All notes are arranged in increasing pitch order.

## Input Format
- First line: integer `n`.  
- Second line: `n` integers representing pitches.

## Output Format
Sorted note pitches separated by a space.

## Constraints
0 <= n <= 50000  
-100000 <= node.val <= 100000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sorting, merge-sort
