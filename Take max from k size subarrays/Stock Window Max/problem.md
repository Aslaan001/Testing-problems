## Title
Stock Window Max

## Slug
stock-window-max

## Difficulty
Easy

## Description
A trader monitors stock prices for `n` days.  
He wants to find the `maximum sum of prices` for any `k` consecutive days` to predict the most profitable streak.

Return that maximum sum.

## Examples

### 1
#### Input
6
4 1 2 10 2 3
3

#### Output
15

#### Explanation
Windows: `[4,1,2]=7`, `[1,2,10]=13`, `[2,10,2]=14`, `[10,2,3]=15`.  
Maximum = `15`.

## Input Format
- First line: integer `n` — days.  
- Second line: `n` integers — stock prices.  
- Third line: integer `k` — window size.

## Output Format
Integer — maximum total price.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ price[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
