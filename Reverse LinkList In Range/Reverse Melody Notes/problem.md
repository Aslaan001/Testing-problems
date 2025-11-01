## Title
Reverse Melody Notes

## Slug
reverse-melody-notes

## Difficulty
Medium

## Description

A composer writes a melody as a sequence of musical notes.  
Given the `head` of the melody and two integers `m` and `n`, reverse the order of notes from position `m` to position `n`.

`Details:`
* Positions are 1-indexed (i.e., the first note is position 1).
* It is guaranteed that `1 <= m <= n <= length` of the melody.

## Examples

### 1

#### Input
5
1 2 3 4 5
2 4

#### Output
1 4 3 2 5

#### Explanation
Melody: `1 -> 2 -> 3 -> 4 -> 5`.  
Reverse notes 2–4 → `4 -> 3 -> 2`.  
Final: `1 -> 4 -> 3 -> 2 -> 5`.

### 2

#### Input
3
1 2 3
1 3

#### Output
3 2 1

#### Explanation
Entire melody reversed.

### 3

#### Input
1
9
1 1

#### Output
9

#### Explanation
Only one note; unchanged.

## Input Format
-   First line: integer `n` — number of notes in the melody.
-   Second line: `n` integers representing note values.
-   Third line: two integers `m` and `n` — start and end positions to reverse.

## Output Format
For each test case, print all notes in the modified melody separated by spaces.

## Constraints
- 1 <= n <= 500
- 1 <= m <= n
- -5000 <= note.val <= 5000

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, two-pointers, reversal
