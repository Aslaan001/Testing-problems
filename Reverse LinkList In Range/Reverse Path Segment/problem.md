## Title
Reverse Path Segment

## Slug
reverse-path-segment

## Difficulty
Medium

## Description

A traveler walks along a numbered path of waypoints.  
Given the `head` of the path and two integers `m` and `n`, reverse the waypoints from position `m` to position `n`.

`Details:`
* Positions are 1-indexed (i.e., waypoint 1 is the start).
* It is guaranteed that `1 <= m <= n <= total waypoints`.

## Examples

### 1

#### Input
5
1 2 3 4 5
2 4

#### Output
1 4 3 2 5

#### Explanation
Path: `1 -> 2 -> 3 -> 4 -> 5`.  
Reversing waypoints 2–4 gives `1 -> 4 -> 3 -> 2 -> 5`.

### 2

#### Input
3
1 2 3
1 3

#### Output
3 2 1

#### Explanation
Entire path reversed.

### 3

#### Input
1
10
1 1

#### Output
10

#### Explanation
Only one waypoint; unchanged.

## Input Format
-   First line: integer `n` — number of waypoints.
-   Second line: `n` integers representing waypoint values.
-   Third line: two integers `m` and `n` — start and end positions to reverse.

## Output Format
For each test case, print all waypoints in the modified path separated by spaces.

## Constraints
- 1 <= n <= 500
- 1 <= m <= n
- -5000 <= waypoint.val <= 5000

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, two-pointers, reversal
