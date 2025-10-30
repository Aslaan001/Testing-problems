## Title
Rainfall Sum Max

## Slug
rainfall-sum-max

## Difficulty
Easy

## Description
You are analyzing weather data. Each number in the sequence represents the rainfall in millimeters for one day.  

Find the `maximum total rainfall` recorded over `k` consecutive days`.

Return this value.

## Examples

### 1
#### Input
5
1 2 3 4 5
2

#### Output
9

#### Explanation
Rainfall totals: `[1,2]=3`, `[2,3]=5`, `[3,4]=7`, `[4,5]=9`.  
Maximum = `9`.

## Input Format
- First line: integer `n` — number of days.  
- Second line: `n` integers — rainfall per day.  
- Third line: integer `k` — window size.

## Output Format
A single integer — maximum rainfall sum.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ rainfall[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
