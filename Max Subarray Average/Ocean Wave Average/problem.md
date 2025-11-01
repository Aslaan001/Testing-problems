## Title
Ocean Wave Average

## Slug
ocean-wave-average

## Difficulty
Easy

## Description

In the vast ocean, each wave has a strength value representing its height and power.  
You are the Ocean Observer, and your task is to find a stretch of exactly `k` consecutive waves that have the highest average strength.

Return this maximum average strength, accurate up to 10⁻⁵.

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
Only one wave exists, so the average is `5.00000`.

## Input Format
- First line: integer `n` — number of waves.  
- Second line: `n` space-separated integers — representing wave strengths.  
- Third line: integer `k` — length of the consecutive segment.

## Output Format
Return the maximum average strength (accurate to 5 decimal places).

## Constraints
- 1 ≤ n ≤ 1e4  
- 1 ≤ k ≤ n  
- -10⁴ ≤ strength[i] ≤ 10⁴  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
sliding-window, arrays
