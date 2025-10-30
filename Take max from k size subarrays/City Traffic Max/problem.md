## Title
City Traffic Max

## Slug
city-traffic-max

## Difficulty
Easy

## Description
A city monitors the number of vehicles passing through a checkpoint each hour.  
Find the `maximum total traffic` over any `k` consecutive hours`.

Return that total.

## Examples

### 1
#### Input
6
4 1 2 10 2 3
3

#### Output
15

#### Explanation
Traffic totals: `[4,1,2]=7`, `[1,2,10]=13`, `[2,10,2]=14`, `[10,2,3]=15`.  
Maximum = `15`.

## Input Format
- First line: integer `n` — total hours.  
- Second line: `n` integers — vehicle counts.  
- Third line: integer `k` — time window.

## Output Format
Single integer — maximum traffic count.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ count[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
