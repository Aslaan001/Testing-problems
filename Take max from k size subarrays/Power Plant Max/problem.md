## Title
Power Plant Max

## Slug
power-plant-max

## Difficulty
Easy

## Description
Each generator in a power plant produces a certain amount of power per day.  
Find the `maximum total power` produced by any `k` consecutive generators`.

Return the total.

## Examples

### 1
#### Input
5
1 2 3 4 5
2

#### Output
9

#### Explanation
Power sums: `[1,2]=3`, `[2,3]=5`, `[3,4]=7`, `[4,5]=9`.  
Maximum = `9`.

## Input Format
- First line: integer `n` — number of generators.  
- Second line: `n` integers — power outputs.  
- Third line: integer `k` — number of consecutive generators.

## Output Format
Integer — maximum power output.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ power[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
