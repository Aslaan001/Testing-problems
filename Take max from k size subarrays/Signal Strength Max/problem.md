## Title
Signal Strength Max

## Slug
signal-strength-max

## Difficulty
Easy

## Description
You are analyzing a data signal measured at different time intervals.  
Find the `maximum total signal strength` across any `k` consecutive measurements`.

Return that value.

## Examples

### 1
#### Input
6
4 1 2 10 2 3
3

#### Output
15

#### Explanation
Signal segments: `[4,1,2]=7`, `[1,2,10]=13`, `[2,10,2]=14`, `[10,2,3]=15`.  
Maximum = `15`.

## Input Format
- First line: integer `n` — number of measurements.  
- Second line: `n` integers — signal strengths.  
- Third line: integer `k` — consecutive measurements.

## Output Format
Single integer — maximum total signal.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ signal[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
