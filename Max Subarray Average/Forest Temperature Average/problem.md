## Title
Forest Temperature Average

## Slug
forest-temperature-average

## Difficulty
Easy

## Description

A meteorologist records temperature readings across a dense forest.  
You need to find the stretch of `k` consecutive readings with the highest average temperature.

Return this maximum average, accurate up to 10⁻⁵.

## Examples

### 1
#### Input
6  
1 12 -5 -6 50 3  
4  

#### Output
12.75000  

#### Explanation
The section `[12, -5, -6, 50]` gives the maximum average: (12 - 5 - 6 + 50)/4 = 12.75

### 2
#### Input
1  
5  
1  

#### Output
5.00000  

#### Explanation
Only one reading — average = 5.00000.

## Input Format
- First line: integer `n` — number of readings.  
- Second line: `n` integers — temperature values.  
- Third line: integer `k` — size of the segment.

## Output Format
Return the maximum average temperature (to 5 decimals).

## Constraints
- 1 ≤ n ≤ 1e4  
- 1 ≤ k ≤ n  
- -10⁴ ≤ temp[i] ≤ 10⁴  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
sliding-window, arrays
