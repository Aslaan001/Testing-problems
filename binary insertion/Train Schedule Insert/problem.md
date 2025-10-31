## Title

Train Schedule Insert

## Slug

train-schedule-insert

## Difficulty

Medium

## Description

A railway control system keeps a sorted list of train departure times (in minutes).  
A new train has been added — find where its departure time should be inserted to maintain sorted order.

Use `binary search` for efficient insertion.

Return the `0-based index` of the correct insertion position.

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

- First line: two integers `n` and `key` — number of trains and new train time.  
- Second line: `n` integers — sorted times.

## Output Format  

- Single integer — the insertion index.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  
- Times are sorted and unique.  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
