## Title

Genome Sequence Insert

## Slug

genome-sequence-insert

## Difficulty

Medium

## Description

A biologist maintains a sorted list of genome markers arranged by their unique numerical code.  
A new marker has been discovered — you must find where to insert it so the sequence remains sorted.

Use `binary search` to efficiently find the insertion point.

Return the `0-based index` where the marker should be placed.

## Examples

### 1

#### Input

5 4
1 3 5 6 8

#### Output
2

#### Explanation

The genome marker `4` should be inserted at index `2` to preserve the sorted order.

### 2

#### Input

4 1
2 4 6 8 

#### Output
0

#### Explanation

The marker `1` should be placed at index `0` before all others.

## Input Format  

- First line: two integers `n` and `key` — number of markers and new marker code.  
- Second line: `n` sorted integers — existing genome codes.

## Output Format  

- A single integer — the insertion index.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  
- The array is sorted and contains distinct elements.  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
