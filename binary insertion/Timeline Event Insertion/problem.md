## Title

Timeline Event Insertion

## Slug

timeline-event-insertion

## Difficulty

Medium

## Description

A historian keeps a timeline of important events in ascending chronological order.  
You are given a new event’s year and must find where to insert it so that the timeline remains sorted.

Use `binary search` for efficiency.

Return the `0-based index` where it should be inserted.

## Examples

### 1

#### Input

5 4
1 3 5 6 8

#### Output
2

### 2

#### Input

4 1
2 4 6 8 

#### Output
0

## Input Format  

- Line 1: integers `n` and `key`.  
- Line 2: sorted event years.

## Output Format  

- A single integer — insertion index.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
