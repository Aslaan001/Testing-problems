## Title

Crystal Index Locator

## Slug

crystal-index-locator

## Difficulty

Medium

## Description

In the Crystal Archives, magical crystals are stored in ascending order of their power.  
You have discovered a new crystal with a specific power level and must find the exact position where it should be inserted so that the archive remains sorted.  

Use `binary search` to efficiently determine the correct position.

Return the `0-based index` where the crystal should be placed.

## Examples

### 1

#### Input

5 4
1 3 5 6 8

#### Output
2

#### Explanation

The new crystal with power `4` fits at index `2`: `[1, 3, 4, 5, 6, 8]`.

### 2

#### Input

4 1
2 4 6 8 

#### Output
0

#### Explanation

Power `1` should be inserted at index `0`: `[1, 2, 4, 6, 8]`.

## Input Format  

- First line: two integers `n` and `key` — the number of crystals and the power of the new one.  
- Second line: `n` space-separated integers representing crystal powers in sorted order.

## Output Format  

- A single integer — the index where the new crystal should be inserted.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  
- `arr` is sorted in ascending order with distinct values.  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
