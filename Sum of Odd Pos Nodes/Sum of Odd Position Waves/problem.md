## Title
Sum of Odd Position Waves

## Slug
sum-of-odd-position-waves

## Difficulty
Easy

## Description

In an ocean simulation, waves are recorded sequentially with their heights.  
Your goal is to find the total height of waves that appear at `odd positions`.

Positions are `1-based`.

Return the total wave height of all odd-positioned waves.

## Examples

### 1
#### Input
5  
10 20 30 40 50  

#### Output
90  

#### Explanation
Waves at odd positions: 10, 30, 50.  
Sum = 90.

### 2
#### Input
4  
5 15 25 35  

#### Output
30  

#### Explanation
Waves at odd positions: 5, 25.  
Sum = 30.

## Input Format
- First line: integer `n` — number of waves.  
- Second line: `n` integers representing wave heights.

## Output Format
Return the total height of waves at odd positions.

## Constraints
- 1 ≤ n ≤ 1000  
- 0 ≤ height ≤ 1000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sum, basic
