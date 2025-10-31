## Title

Ship Cargo Locator

## Slug

ship-cargo-locator

## Difficulty

Easy

## Description

A cargo ship maintains sorted records of container IDs in `non-decreasing order`.  
Find whether a container with ID `k` exists in `cargo`.  

Return its `index` if found, otherwise `-1`.  

`Note: Use '0' based indexing`.

## Examples

### 1

#### Input

5  
5 10 15 20 25  
15

#### Output

2

#### Explanation

Container 15 is at index 2.

### 2

#### Input

5  
1 3 5 7 9  
4

#### Output

-1

#### Explanation

No container has ID 4.

## Input Format  

- First line: sorted array `cargo[]`.  
- Second line: integer `k` — container ID.

## Output Format  

Return `index` if found, else `-1`.

## Constraints  

- 1 ≤ n ≤ 1e4  
- 1 ≤ arr[i] ≤ 1e9  
- 0 ≤ k ≤ 1e9  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

binary-search, arrays.
