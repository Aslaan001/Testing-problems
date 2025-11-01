## Title
Sum of Odd Position Planets

## Slug
sum-of-odd-position-planets

## Difficulty
Easy

## Description

In a solar system model, planets are aligned in a sequence with given mass values.  
Your mission is to find the total mass of planets that appear at `odd positions` in this model.

Positions are `1-based`.

Return the sum of masses of planets at odd positions.

## Examples

### 1
#### Input
5  
10 20 30 40 50  

#### Output
90  

#### Explanation
Planets at odd positions: 10, 30, 50.  
Sum = 90.

### 2
#### Input
4  
5 15 25 35  

#### Output
30  

#### Explanation
Planets at odd positions: 5, 25.  
Sum = 30.

## Input Format
- First line: integer `n` — number of planets.  
- Second line: `n` integers representing planet masses.

## Output Format
Return the total mass of planets at odd positions.

## Constraints
- 1 ≤ n ≤ 1000  
- 0 ≤ mass ≤ 1000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sum, basic
