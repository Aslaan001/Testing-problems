## Title

Find the Missing Puzzle Level

## Slug

find-missing-puzzle-level

## Difficulty

Easy

## Description

You are designing a puzzle game with levels starting from 0.  
Some levels are already available to players.  

Find the first level that has **not** been created yet — the `MEX` of the level numbers.

## Examples

### 1

#### Input

5  
0 1 2 4 5

#### Output
3

#### Explanation
Levels 0–2 and 4–5 exist.  
Level `3` is missing.

### 2

#### Input

4  
0 1 2 3

#### Output
4

#### Explanation
Next missing level is `4`.

## Input Format

- First line: integer `n` — number of existing levels.  
- Second line: `n` integers `arr[i]` — level numbers.

## Output Format

- A single integer — the first missing level.

## Constraints

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
