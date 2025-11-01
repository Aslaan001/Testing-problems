## Title
Reverse Spell Sequence

## Slug
reverse-spell-sequence

## Difficulty
Medium

## Description

A mage prepares a list of spells to cast.  
Given the `head` of the spell list and integers `m` and `n`, reverse the spells from position `m` to position `n`.

`Details:`
* Positions are 1-indexed (i.e., `m=1` is the first spell).
* It is guaranteed that `1 <= m <= n <= length` of the list.

## Examples

### 1

#### Input
5
1 2 3 4 5
2 4

#### Output
1 4 3 2 5

#### Explanation
`1 -> 2 -> 3 -> 4 -> 5` becomes `1 -> 4 -> 3 -> 2 -> 5` after reversing 2–4.

### 2

#### Input
3
1 2 3
1 3

#### Output
3 2 1

#### Explanation
All spells are reversed.

### 3

#### Input
1
6
1 1

#### Output
6

#### Explanation
Single spell, no change.

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
