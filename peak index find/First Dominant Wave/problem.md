## Title

First Dominant Wave

## Slug

first-dominant-wave

## Difficulty

Medium

## Description

You are observing ocean waves represented as an array of wave heights.  
Each number indicates how high a wave rises at a given time.

Find the first dominant wave index i such that:

- The sum of all previous waves is less than the height of wave i.  
- The sum of all following waves is also less than the height of wave i.

If no such dominant wave exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Wave 1 dominates: left sum = 1 < 5, right sum = 3 < 5 → output 1.

### 2

#### Input
5
2 4 3 1 2

#### Output
-1

#### Explanation
No wave satisfies the dominance condition.

## Input Format
- First line: integer n — number of waves.  
- Second line: n integers — wave heights.

## Output Format
- A single integer — the first dominant wave index or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
