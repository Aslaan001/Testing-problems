## Title
Reverse Athlete Lineup

## Slug
reverse-athlete-lineup

## Difficulty
Medium

## Description

Athletes line up for a relay.  
Given the `head` of the lineup and two integers `m` and `n`, reverse the runners standing from position `m` to position `n`.

`Details:`
* Positions are 1-indexed (i.e., `m=1` is the head runner).
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
Original lineup: `1 -> 2 -> 3 -> 4 -> 5`.
Reverse positions 2–4 to get `1 -> 4 -> 3 -> 2 -> 5`.

### 2

#### Input
3
1 2 3
1 3

#### Output
3 2 1

#### Explanation
Entire lineup reversed.

### 3

#### Input
1
7
1 1

#### Output
7

#### Explanation
Only one athlete; unchanged.

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
