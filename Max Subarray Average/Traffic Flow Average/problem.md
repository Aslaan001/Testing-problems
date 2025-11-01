## Title
Traffic Flow Average

## Slug
traffic-flow-average

## Difficulty
Easy

## Description

Sensors on a highway record vehicle counts over time.  
Identify exactly `k` consecutive intervals with the highest average traffic flow.

Return this maximum average flow, accurate up to 10⁻⁵.

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

Only one interval exists, so the average is `5.00000`.

## Input Format  

- First line: integer `n` — the number of intervals.  
- Second line: `n` space-separated integers — vehicle counts.  
- Third line: integer `k` — the length of the subarray to consider.

## Output Format  

- Return the `maximum average value` (accurate to 5 decimal places).  

## Constraints  

- 1 ≤ n ≤ 1e4
- 1 ≤ k ≤ n  
- -10⁴ ≤ cars[i] ≤ 10⁴  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

sliding-window, arrays
