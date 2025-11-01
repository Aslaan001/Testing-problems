## Title
Student Score Average

## Slug
student-score-average

## Difficulty
Easy

## Description

A teacher keeps track of a student's test scores.  
Determine the `k` consecutive tests with the highest average score.

Return this maximum average, accurate up to 10⁻⁵.

## Examples

### 1
#### Input
6
1 12 -5 -6 50 3
4

#### Output
12.75000

#### Explanation
Best scores `[12, -5, -6, 50]` yield (12 - 5 - 6 + 50)/4 = 12.75.

### 2
#### Input
1
5
1

#### Output
5.00000

#### Explanation
Single test — average = 5.00000.

## Input Format
- First line: integer `n` — number of tests.  
- Second line: `n` integers representing scores.  
- Third line: integer `k`.

## Output Format
Return the maximum average score.

## Constraints
- 1 ≤ n ≤ 1e4  
- 1 ≤ k ≤ n  
- -10⁴ ≤ score[i] ≤ 10⁴  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
sliding-window, arrays
