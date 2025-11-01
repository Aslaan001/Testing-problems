## Title
Reverse Mission Queue

## Slug
reverse-mission-queue

## Difficulty
Medium

## Description

Agents receive missions in a queue.  
Given the `head` of the mission queue and two integers `m` and `n`, reverse the missions from position `m` to position `n`.

`Details:`
* Positions are 1-indexed.
* It is guaranteed that `1 <= m <= n <= length` of the queue.

## Examples

### 1

#### Input
5
1 2 3 4 5
2 4

#### Output
1 4 3 2 5

#### Explanation
Reverse the subqueue 2–4: `2 -> 3 -> 4` → `4 -> 3 -> 2`.

### 2

#### Input
3
1 2 3
1 3

#### Output
3 2 1

#### Explanation
Complete reversal of the queue.

### 3

#### Input
1
8
1 1

#### Output
8

#### Explanation
Single mission; unchanged.

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
