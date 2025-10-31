## Title

Warehouse Item Insert

## Slug

warehouse-item-insert

## Difficulty

Medium

## Description

A warehouse system stores item IDs in sorted order for efficient lookup.  
A new shipment arrives with an item that must be placed in its correct sorted location.

Use `binary search` to determine where it belongs.

Return the `0-based index` of insertion.

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

- First line: two integers `n` and `key`.  
- Second line: sorted item IDs.

## Output Format  

- Integer — position for insertion.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
