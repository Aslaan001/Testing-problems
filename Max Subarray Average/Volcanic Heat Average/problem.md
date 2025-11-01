## Title
Volcanic Heat Average

## Slug
volcanic-heat-average

## Difficulty
Easy

## Description

Researchers measure volcanic heat over time.  
Find the `k` consecutive measurements with the highest average heat.

Return this maximum average temperature, accurate up to 10⁻⁵.

## Examples

### 1
#### Input
6
1 12 -5 -6 50 3
4

#### Output
12.75000

#### Explanation
Segment `[12, -5, -6, 50]` gives max average (12 - 5 - 6 + 50)/4 = 12.75.

### 2
#### Input
1
5
1

#### Output
5.00000

#### Explanation
Only one reading; average = 5.00000.

## Input Format
- First line: integer `n` — number of readings.  
- Second line: `n` integers.  
- Third line: integer `k`.

## Output Format
Return the maximum average heat value.

## Constraints
- 1 ≤ n ≤ 1e4  
- 1 ≤ k ≤ n  
- -10⁴ ≤ heat[i] ≤ 10⁴  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
sliding-window, arrays
s