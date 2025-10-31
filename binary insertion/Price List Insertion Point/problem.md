## Title

Price List Insertion Point

## Slug

price-list-insertion-point

## Difficulty

Medium

## Description

A store keeps product prices sorted in ascending order.  
When a new product is added, find where its price should be inserted so the list remains sorted.

Use `binary search` to determine the correct position.

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

- Line 1: integers `n` and `key`.  
- Line 2: sorted prices.

## Output Format  

- Integer — index to insert new price.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
