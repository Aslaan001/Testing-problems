## Title
Sum of Odd Position Stars

## Slug
sum-of-odd-position-stars

## Difficulty
Easy

## Description

In the vast universe, a galaxy chain contains several stars aligned in sequence.  
Your mission as an astronomer is to calculate the total brightness of all stars located at `odd positions` in the galactic chain.  

Positions are `1-based`, meaning the first star is position `1`, the second is `2`, and so on.  

Return the sum of brightness values of stars at odd positions.

## Examples

### 1

#### Input
5  
10 20 30 40 50  

#### Output
90  

#### Explanation
Stars at odd positions are `10`, `30`, and `50`.  
Sum = 10 + 30 + 50 = 90.

### 2

#### Input
4  
5 15 25 35  

#### Output
30  

#### Explanation
Stars at odd positions are `5` and `25`.  
Sum = 5 + 25 = 30.

## Input Format
- First line: integer `n` — the number of stars in the chain.  
- Second line: `n` integers representing brightness values.

## Output Format
Return the sum of brightness values at odd positions.

## Constraints
- 1 ≤ n ≤ 1000  
- 0 ≤ star.brightness ≤ 1000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sum, basic
