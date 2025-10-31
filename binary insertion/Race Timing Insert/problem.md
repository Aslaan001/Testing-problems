## Title

Race Timing Insert

## Slug

race-timing-insert

## Difficulty

Medium

## Description

During a marathon, the finish times of runners are stored in ascending order.  
You need to insert a new runner’s finish time while keeping the order intact.

Use `binary search` to find the correct insertion point.

Return the `0-based index` where it belongs.

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
- Line 2: sorted finish times.

## Output Format  

- Integer — insertion index.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
