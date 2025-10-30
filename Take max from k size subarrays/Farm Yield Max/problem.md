## Title
Farm Yield Max

## Slug
farm-yield-max

## Difficulty
Easy

## Description
A farmer records the yield of crops from each field in a long row.  
You need to find the `maximum total yield` from any `k` consecutive fields`.

Return that maximum yield.

## Examples

### 1
#### Input
5
1 2 3 4 5
2

#### Output
9

#### Explanation
Possible consecutive yields: `[1,2]=3`, `[2,3]=5`, `[3,4]=7`, `[4,5]=9`.  
Maximum = `9`.

## Input Format
- First line: integer `n` — total number of fields.  
- Second line: `n` integers — yield per field.  
- Third line: integer `k` — consecutive fields.

## Output Format
A single integer — maximum total yield.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ yield[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
