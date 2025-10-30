## Title
Game Score Max

## Slug
game-score-max

## Difficulty
Easy

## Description
In a video game tournament, your scores are recorded after each round.  
You must find the `maximum total score` in any `k` consecutive rounds`.

Return that maximum.

## Examples

### 1
#### Input
5
1 2 3 4 5
2

#### Output
9

#### Explanation
Rounds: `[1,2]=3`, `[2,3]=5`, `[3,4]=7`, `[4,5]=9`.  
Maximum = `9`.

## Input Format
- First line: integer `n` — total rounds.  
- Second line: `n` integers — scores.  
- Third line: integer `k` — consecutive rounds.

## Output Format
Integer — maximum total score.

## Constraints
- 1 ≤ n ≤ 1e4  
- -1e9 ≤ score[i] ≤ 1e9  
- 0 ≤ k ≤ 1e4  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
arrays, sliding-window
