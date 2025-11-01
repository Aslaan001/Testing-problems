## Title
City Pollution Average

## Slug
city-pollution-average

## Difficulty
Easy

## Description

Environmental analysts record pollution levels daily.  
Find the `k` consecutive days with the highest average pollution index.

Return this maximum average index, accurate up to 10⁻⁵.

## Examples

### 1
#### Input
6
1 12 -5 -6 50 3
4

#### Output
12.75000

#### Explanation
Days `[12, -5, -6, 50]` → (12 - 5 - 6 + 50)/4 = 12.75.

### 2
#### Input
1
5
1

#### Output
5.00000

#### Explanation
Only one day, average = 5.00000.

## Input Format
- First line: integer `n` — number of days.  
- Second line: `n` integers representing pollution levels.  
- Third line: integer `k`.

## Output Format
Return the highest average pollution index.

## Constraints
- 1 ≤ n ≤ 1e4  
- 1 ≤ k ≤ n  
- -10⁴ ≤ pollution[i] ≤ 10⁴  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
sliding-window, arrays
