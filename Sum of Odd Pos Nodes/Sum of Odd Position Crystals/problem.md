## Title
Sum of Odd Position Crystals

## Slug
sum-of-odd-position-crystals

## Difficulty
Easy

## Description

Inside a mystical cave, glowing crystals are arranged in a straight chain.  
Each crystal emits a light value, and you must find the total light of crystals placed at `odd positions`.

Positions are `1-based`.

Return the total light emitted by crystals at odd positions.

## Examples

### 1

#### Input
5  
10 20 30 40 50  

#### Output
90  

#### Explanation
Crystals at odd positions: 10, 30, 50.  
Sum = 90.

### 2

#### Input
4  
5 15 25 35  

#### Output
30  

#### Explanation
Crystals at odd positions: 5, 25.  
Sum = 30.

## Input Format
- First line: integer `n` — number of crystals.  
- Second line: `n` integers representing the brightness of each crystal.

## Output Format
Return the total light of crystals at odd positions.

## Constraints
- 1 ≤ n ≤ 1000  
- 0 ≤ light ≤ 1000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sum, basic
