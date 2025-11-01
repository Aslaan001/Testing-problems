## Title
Rainfall Average

## Slug
rainfall-average

## Difficulty
Easy

## Description

Meteorologists record daily rainfall amounts.  
You must determine a span of exactly `k` consecutive days whose rainfall has the highest average.

Return this maximum average rainfall, accurate up to 10⁻⁵.

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

- First line: integer `n` — the number of rainfall measurements.  
- Second line: `n` space-separated integers — rainfall amounts.  
- Third line: integer `k` — the length of the subarray to consider.

## Output Format  

- Return the `maximum average value` (accurate to 5 decimal places).  

## Constraints  

- 1 ≤ n ≤ 1e4
- 1 ≤ k ≤ n  
- -10⁴ ≤ rain[i] ≤ 10⁴  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

sliding-window, arrays
