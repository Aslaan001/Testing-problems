## Title
Sum of Odd Position Birds

## Slug
sum-of-odd-position-birds

## Difficulty
Easy

## Description

A bird watcher records birds sitting on a wire in sequence.  
Each bird has a chirping frequency value.  
Find the total frequency of birds sitting at `odd positions`.

Positions are `1-based`.

Return the sum of frequencies of birds at odd positions.

## Examples

### 1
#### Input
5  
10 20 30 40 50  

#### Output
90  

#### Explanation
Birds at odd positions: 10, 30, 50.  
Sum = 90.

### 2
#### Input
4  
5 15 25 35  

#### Output
30  

#### Explanation
Birds at odd positions: 5, 25.  
Sum = 30.

## Input Format
- First line: integer `n` — number of birds.  
- Second line: `n` integers representing their frequencies.

## Output Format
Return the total frequency of birds at odd positions.

## Constraints
- 1 ≤ n ≤ 1000  
- 0 ≤ frequency ≤ 1000  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
linked-list, sum, basic
