## Title
Reverse Car Parade Segment

## Slug
reverse-car-parade-segment

## Difficulty
Medium

## Description

Cars are lined up for a parade.  
Given the `head` of the lineup and two integers `m` and `n`, reverse the cars from position `m` to position `n`.

`Details:`
* Positions are 1-indexed.
* It is guaranteed that `1 <= m <= n <= length` of the lineup.

## Examples

### 1

#### Input
5
1 2 3 4 5
2 4

#### Output
1 4 3 2 5

#### Explanation
Reverse the segment 2–4 to obtain `1 -> 4 -> 3 -> 2 -> 5`.

### 2

#### Input
3
1 2 3
1 3

#### Output
3 2 1

#### Explanation
Whole lineup reversed.

### 3

#### Input
1
4
1 1

#### Output
4

#### Explanation
One car only; no change.

## Input Format
-   First line: integer `n` — number of nodes in the linked list.
-   Second line: `n` integers representing the node values.
-   Third line: two integers `m` and `n` — the start and end positions for reversal.

## Output Format
For each test case, print the data of all nodes in the modified linked list on a new line, separated by a single space.

## Constraints
- 1 <= n <= 500
- 1 <= m <= n
- -5000 <= node.val <= 5000

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, two-pointers, reversal
