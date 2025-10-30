## Title
River Flow Max

## Slug
river-flow-max

## Difficulty
Easy

## Description
Hydrologists recorded river flow rates daily.  
Find the `maximum total flow` over any `k` consecutive days`.

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
Flows: `[4,1,2]=7`, `[1,2,10]=13`, `[2,10,2]=14`, `[10,2,3]=15`.  
Maximum = `15`.

## Input Format
- First line: integer `n` — number of days.  
- Second line: `n` integers — flow rates.  
- Third line: integer `k` — period length.

## Output Format
Integer — maximum total flow.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ flow[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
