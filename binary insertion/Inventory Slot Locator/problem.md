## Title

Inventory Slot Locator

## Slug

inventory-slot-locator

## Difficulty

Medium

## Description

In a game inventory system, item levels are stored in ascending order.  
When a new item appears, find the correct slot to insert it so the list remains sorted.

Use `binary search` to find the position.

Return the `0-based index`.

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

- First line: integers `n` and `key`.  
- Second line: sorted item levels.

## Output Format  

- Integer — index to insert.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
