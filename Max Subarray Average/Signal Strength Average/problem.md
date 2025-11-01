## Title
Signal Strength Average

## Slug
signal-strength-average

## Difficulty
Easy

## Description

A satellite sends varying signal strengths during transmission.  
Your task is to determine the `k` consecutive signals that produce the highest average strength.

Return the maximum average signal strength, accurate up to 10⁻⁵.

## Examples

### 1
#### Input
6
1 12 -5 -6 50 3
4

#### Output
12.75000

#### Explanation
Strongest signals `[12, -5, -6, 50]` yield (12 - 5 - 6 + 50) / 4 = 12.75.

### 2
#### Input
1
5
1

#### Output
5.00000

#### Explanation
Only one signal, average = 5.00000.

## Input Format
- First line: integer `n` — number of signal readings.  
- Second line: `n` integers representing signal strengths.  
- Third line: integer `k`.

## Output Format
Return the highest average signal strength.

## Constraints
- 1 ≤ n ≤ 1e4  
- 1 ≤ k ≤ n  
- -10⁴ ≤ signal[i] ≤ 10⁴  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
sliding-window, arrays
