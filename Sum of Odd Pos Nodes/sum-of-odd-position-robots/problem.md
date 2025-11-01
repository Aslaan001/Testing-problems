## Title
Sum of Odd Position Robots

## Slug
sum-of-odd-position-robots

## Difficulty
Easy

## Description

A production line has several robots working in sequence.  
Each robot processes a certain number of items per minute.  
Find the total items processed by robots at `odd positions`.

Positions are `1-based`.

Return the total processed items of robots at odd positions.

## Examples

### 1
#### Input
5  
10 20 30 40 50  

#### Output
90  

#### Explanation
Robots at odd positions: 10, 30, 50.  
Sum = 90.

### 2
#### Input
4  
5 15 25 35  

#### Output
30  

#### Explanation
Robots at odd positions: 5, 25.  
Sum = 30.

## Input Format
- First line: integer `n` — number of robots.  
- Second line: `n` integers representing items processed.

## Output Format
Return the total items processed by robots at odd positions.

## Constraints
- 1 ≤ n ≤ 1000  
- 0 ≤ items ≤ 1000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sum, basic
