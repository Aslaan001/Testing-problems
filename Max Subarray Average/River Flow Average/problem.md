## Title
River Flow Average

## Slug
river-flow-average

## Difficulty
Easy

## Description

A hydrologist monitors the flow rates of a mighty river at different time intervals.  
Your goal is to find `k` consecutive readings that produce the highest average flow rate.

Return this maximum average flow rate, accurate up to 10⁻⁵.

## Examples

### 1
#### Input
6
1 12 -5 -6 50 3
4

#### Output
12.75000

#### Explanation
Flow readings `[12, -5, -6, 50]` yield (12 - 5 - 6 + 50) / 4 = 12.75.

### 2
#### Input
1
5
1

#### Output
5.00000

#### Explanation
Single flow reading, average = 5.00000.

## Input Format
- First line: integer `n` — number of readings.  
- Second line: `n` integers representing flow rates.  
- Third line: integer `k`.

## Output Format
Return the maximum average flow rate.

## Constraints
- 1 ≤ n ≤ 1e4  
- 1 ≤ k ≤ n  
- -10⁴ ≤ flow[i] ≤ 10⁴  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
sliding-window, arrays
