## Title
Kingdom Gold Average

## Slug
kingdom-gold-average

## Difficulty
Easy

## Description

In the Royal Kingdom, each day the treasury reports its gold collection value.  
You, as the Royal Accountant, must find the sequence of `k` consecutive days that yields the highest average gold gain.

Return the maximum average amount, accurate up to 10⁻⁵.

## Examples

### 1

#### Input
6  
1 12 -5 -6 50 3  
4  

#### Output
12.75000  

#### Explanation
Days `[12, -5, -6, 50]` yield the highest average:  
(12 - 5 - 6 + 50) / 4 = 12.75

### 2

#### Input
1  
5  
1  

#### Output
5.00000  

#### Explanation
Only one day's value exists, so the average is `5.00000`.

## Input Format
- First line: integer `n` — number of recorded days.  
- Second line: `n` space-separated integers — gold collected each day.  
- Third line: integer `k` — length of the period.

## Output Format
Return the maximum average gold collected over `k` days.

## Constraints
- 1 ≤ n ≤ 1e4  
- 1 ≤ k ≤ n  
- -10⁴ ≤ gold[i] ≤ 10⁴  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
sliding-window, arrays
