## Title

Leaderboard Rank Finder

## Slug

leaderboard-rank-finder

## Difficulty

Medium

## Description

You are maintaining an online gaming leaderboard where player scores are stored in ascending order.  
A new player joins with a specific score — find the correct rank position for the player such that the leaderboard remains sorted.

Use `binary search` to efficiently find the rank.

Return the `0-based index` where the new score should be inserted.

## Examples

### 1

#### Input

5 4
1 3 5 6 8

#### Output
2

#### Explanation

Player score `4` fits between `3` and `5`, giving index `2`.

### 2

#### Input

4 1
2 4 6 8 

#### Output
0

#### Explanation

Score `1` should be placed at index `0` to maintain sorted order.

## Input Format  

- First line: two integers `n` and `key` — number of players and the new score.  
- Second line: `n` sorted integers representing existing scores.

## Output Format  

- A single integer — index where the new score should be inserted.

## Constraints  

- 1 ≤ n ≤ 10⁵  
- -10⁹ ≤ arr[i], key ≤ 10⁹  
- Scores are sorted and distinct.  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, binary-search
