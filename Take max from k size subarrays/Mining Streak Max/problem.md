## Title
Mining Streak Max

## Slug
mining-streak-max

## Difficulty
Easy

## Description
You work in a deep mine extracting ores each day.  
Every number represents the amount of ore mined that day.  
Find the `maximum total ore` mined in any `k` consecutive days`.

Return the result.

## Examples

### 1
#### Input
6
4 1 2 10 2 3
3

#### Output
15

#### Explanation
Ore extraction: `[4,1,2]=7`, `[1,2,10]=13`, `[2,10,2]=14`, `[10,2,3]=15`.  
Maximum = `15`.

## Input Format
- First line: integer `n` — number of days.  
- Second line: `n` integers — ore values.  
- Third line: integer `k` — streak size.

## Output Format
Single integer — maximum total ore mined.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ ore[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
