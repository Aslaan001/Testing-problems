## Title
Desert Heat Max

## Slug
desert-heat-max

## Difficulty
Easy

## Description
Researchers recorded temperatures in a desert over several days.  
Find the `maximum total heat index` across any `k` consecutive days`.

Return the hottest total recorded.

## Examples

### 1
#### Input
5
1 2 3 4 5
2

#### Output
9

#### Explanation
2-day windows: `[1,2]=3`, `[2,3]=5`, `[3,4]=7`, `[4,5]=9`.  
Maximum = `9`.

## Input Format
- First line: integer `n` — days recorded.  
- Second line: `n` integers — temperature readings.  
- Third line: integer `k` — number of consecutive days.

## Output Format
A single integer — maximum total heat index.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ temp[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
