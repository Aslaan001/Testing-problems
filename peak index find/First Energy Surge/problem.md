## Title

First Energy Surge

## Slug

first-energy-surge

## Difficulty

Medium

## Description

An energy detector records readings at fixed intervals, stored as integers in an array.  
Your goal is to find the first time where the energy reading is greater than the total energy before and after it.

Find the smallest index i where:

- Sum before i < arr[i]  
- Sum after i < arr[i]

If no such energy surge exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Reading 1 exceeds both previous and following totals.

### 2

#### Input
5
1 2 3 4 5

#### Output
-1

#### Explanation
No surge detected.

## Input Format
- First line: integer n — number of readings.  
- Second line: n integers — energy readings.

## Output Format
- One integer — the index of the first surge or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
