## Title
Sum of Odd Position Gems

## Slug
sum-of-odd-position-gems

## Difficulty
Easy

## Description

Deep inside a treasure cave lies a row of sparkling gems.  
Each gem has a magical value, and your task is to calculate the total of all gem values located at `odd positions`.  

Positions are `1-based`, meaning the first gem is at position `1`, the second at `2`, and so on.  

Return the total value of gems at odd positions.

## Examples

### 1

#### Input
5  
10 20 30 40 50  

#### Output
90  

#### Explanation
Gems at odd positions: `10`, `30`, `50`.  
Sum = 10 + 30 + 50 = 90.

### 2

#### Input
4  
5 15 25 35  

#### Output
30  

#### Explanation
Gems at odd positions are `5` and `25`.  
Sum = 30.

## Input Format
- First line: integer `n` — the number of gems in the treasure line.  
- Second line: `n` integers representing gem values.

## Output Format
Return the total value of gems at odd positions.

## Constraints
- 1 ≤ n ≤ 1000  
- 0 ≤ gem.value ≤ 1000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sum, basic
