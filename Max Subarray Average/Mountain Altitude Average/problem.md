## Title
Mountain Altitude Average

## Slug
mountain-altitude-average

## Difficulty
Easy

## Description

A climber records altitudes while hiking.  
Find the `k` consecutive altitude readings that give the highest average altitude.

Return this maximum average altitude, accurate up to 10⁻⁵.

## Examples

### 1
#### Input
6
1 12 -5 -6 50 3
4

#### Output
12.75000

#### Explanation
Highest section `[12, -5, -6, 50]` → (12 - 5 - 6 + 50)/4 = 12.75.

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
- First line: integer `n` — number of altitude readings.  
- Second line: `n` integers representing altitudes.  
- Third line: integer `k`.

## Output Format
Return the highest average altitude.

## Constraints
- 1 ≤ n ≤ 1e4  
- 1 ≤ k ≤ n  
- -10⁴ ≤ altitude[i] ≤ 10⁴  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
sliding-window, arrays
