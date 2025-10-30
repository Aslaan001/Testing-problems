## Title
Mountain Height Max

## Slug
mountain-height-max

## Difficulty
Easy

## Description
Explorers measured a range of mountain peaks.  
Find the `maximum combined height` among any `k` consecutive peaks`.

Return that total height.

## Examples

### 1
#### Input
6
4 1 2 10 2 3
3

#### Output
15

#### Explanation
Peak groups: `[4,1,2]=7`, `[1,2,10]=13`, `[2,10,2]=14`, `[10,2,3]=15`.  
Maximum = `15`.

## Input Format
- First line: integer `n` — number of peaks.  
- Second line: `n` integers — heights.  
- Third line: integer `k` — group size.

## Output Format
Single integer — maximum total height.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ height[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
