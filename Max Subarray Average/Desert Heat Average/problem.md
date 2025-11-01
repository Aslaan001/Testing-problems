## Title
Desert Heat Average

## Slug
desert-heat-average

## Difficulty
Easy

## Description

In the blazing desert, sensors record heat intensity throughout the day.  
Find the group of `k` consecutive readings with the highest average heat intensity.

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
Maximum average segment `[12, -5, -6, 50]` → (12 - 5 - 6 + 50)/4 = 12.75

### 2
#### Input
1  
5  
1  

#### Output
5.00000  

#### Explanation
Single reading — average = 5.00000.

## Input Format
- First line: integer `n` — number of readings.  
- Second line: `n` space-separated integers.  
- Third line: integer `k`.

## Output Format
Return the highest average heat recorded.

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
