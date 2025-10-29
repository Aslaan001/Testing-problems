## Title

First Treasure Value Peak

## Slug

first-treasure-value-peak

## Difficulty

Medium

## Description

A treasure hunter records the value of treasures found on each island in an array.  
Find the first island where the treasure value is greater than the total value before and after it.

Find the smallest index i such that:

- The sum before i < arr[i]  
- The sum after i < arr[i]

If no such island exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Island 1 holds the highest relative treasure value.

### 2

#### Input
5
1 2 4 3 1

#### Output
-1

#### Explanation
No single island dominates.

## Input Format
- First line: integer n — number of islands.  
- Second line: n integers — treasure values.

## Output Format
- One integer — the index of the first treasure peak or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
