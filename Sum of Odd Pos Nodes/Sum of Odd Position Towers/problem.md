## Title
Sum of Odd Position Towers

## Slug
sum-of-odd-position-towers

## Difficulty
Easy

## Description

In a defense simulation, towers are positioned in a straight line.  
Each tower has a defense power, and you must find the total power of towers located at `odd positions`.

Positions are `1-based`.

Return the total defense power of towers at odd positions.

## Examples

### 1
#### Input
5  
10 20 30 40 50  

#### Output
90  

#### Explanation
Towers at odd positions: 10, 30, 50.  
Sum = 90.

### 2
#### Input
4  
5 15 25 35  

#### Output
30  

#### Explanation
Towers at odd positions: 5, 25.  
Sum = 30.

## Input Format
- First line: integer `n` — number of towers.  
- Second line: `n` integers representing tower power.

## Output Format
Return the total power of towers at odd positions.

## Constraints
- 1 ≤ n ≤ 1000  
- 0 ≤ power ≤ 1000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sum, basic
