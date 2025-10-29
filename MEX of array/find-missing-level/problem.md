## Title

Find the Missing Level

## Slug

find-missing-level

## Difficulty

Easy

## Description

In a video game, players complete levels numbered starting from 0.  

You’re given a list of levels that a player has already completed.  
Your task is to find the first level number that the player has **not** completed yet — also known as the `MEX (Minimum Excludant)` of the list.

Return that level number.

## Examples

### 1

#### Input

5  
0 1 3 4 5

#### Output
2

#### Explanation
Levels 0, 1, 3, 4, 5 are completed.  
The first uncompleted level is `2`.

### 2

#### Input

4  
1 0 2 3

#### Output
4

#### Explanation
Levels 0, 1, 2, 3 are completed.  
The next missing level is `4`.

## Input Format

- First line: integer `n` — number of completed levels.  
- Second line: `n` integers `arr[i]` — level numbers.

## Output Format

- A single integer — the missing level number.

## Constraints

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
