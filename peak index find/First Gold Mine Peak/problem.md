## Title

First Gold Mine Peak

## Slug

first-gold-mine-peak

## Difficulty

Medium

## Description

You are analyzing a sequence of gold mines with different gold values.  
Each integer in the array represents the gold extracted from a mine.

Find the first mine index i where:

- The total gold before i is less than arr[i].  
- The total gold after i is also less than arr[i].

If no such mine exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Mine 1 yields more gold than surrounding mines combined.

### 2

#### Input
5
2 3 3 1 1

#### Output
-1

#### Explanation
No dominant gold mine found.

## Input Format
- First line: integer n — number of mines.  
- Second line: n integers — gold values.

## Output Format
- One integer — the first gold mine index or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
