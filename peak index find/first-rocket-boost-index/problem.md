## Title

First Rocket Boost Index

## Slug

first-rocket-boost-index

## Difficulty

Medium

## Description

A sequence of rocket boosters produces thrusts recorded in an array.  
Find the first booster whose thrust exceeds the total thrust of all boosters before and after it.

Find the smallest index i where:

- The sum before i is less than arr[i].  
- The sum after i is less than arr[i].

If no such booster exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Booster 1 gives the first dominant thrust.

### 2

#### Input
5
2 3 3 4 1

#### Output
-1

#### Explanation
No booster produces dominant thrust.

## Input Format
- First line: integer n — number of boosters.  
- Second line: n integers — thrust levels.

## Output Format
- One integer — the first dominant booster index or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
