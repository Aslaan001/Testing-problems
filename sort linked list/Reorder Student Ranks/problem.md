## Title
Reorder Student Ranks

## Slug
reorder-student-ranks

## Difficulty
Medium

## Description

A list of students is arranged according to their randomly assigned ranks.  
You must sort the linked list of student ranks in ascending order and return the `head` of the sorted list.

## Examples

### 1

#### Input
4
4 2 1 3

#### Output
1 2 3 4

#### Explanation
Ranks are rearranged from `4 -> 2 -> 1 -> 3` to `1 -> 2 -> 3 -> 4`.

### 2

#### Input
5
-1 5 3 4 0

#### Output
-1 0 3 4 5

#### Explanation
Students are sorted according to increasing rank values.

## Input Format
-   First line: integer `n` — number of students.  
-   Second line: `n` integers representing their ranks.

## Output Format
Sorted student ranks printed in ascending order.

## Constraints
0 <= n <= 50000  
-100000 <= node.val <= 100000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sorting, two-pointers, merge-sort
