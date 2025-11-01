## Title
Battery Charge Average

## Slug
battery-charge-average

## Difficulty
Easy

## Description

A lab tracks battery charge levels at regular intervals.  
Find the `k` consecutive measurements with the highest average charge.

Return this maximum average charge, accurate up to 10⁻⁵.

## Examples

### 1

#### Input

6
1 12 -5 -6 50 3
4

#### Output

12.75000

#### Explanation

The subarray `[12, -5, -6, 50]` has the highest average:  
(12 - 5 - 6 + 50) / 4 = 12.75

### 2

#### Input

1
5
1

#### Output

5.00000

#### Explanation

Only one measurement exists, so the average is `5.00000`.

## Input Format  

- First line: integer `n` — the number of measurements.  
- Second line: `n` space-separated integers — charge levels.  
- Third line: integer `k` — the length of the subarray to consider.

## Output Format  

- Return the `maximum average value` (accurate to 5 decimal places).  

## Constraints  

- 1 ≤ n ≤ 1e4
- 1 ≤ k ≤ n  
- -10⁴ ≤ charge[i] ≤ 10⁴  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

sliding-window, arrays
