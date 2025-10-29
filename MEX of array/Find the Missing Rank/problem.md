## Title

Find the Missing Rank

## Slug

find-missing-rank

## Difficulty

Easy

## Description

A competition assigns ranks to players starting from 0.  
You’re given a list of the ranks achieved so far.  

Your task is to find the smallest non-negative rank that hasn’t been assigned yet — the `MEX` of the list.

## Examples

### 1

#### Input

5  
0 1 2 4 5

#### Output
3

#### Explanation
Ranks 0, 1, 2, 4, 5 exist.  
Rank `3` is missing.

### 2

#### Input

3  
0 2 3

#### Output
1

#### Explanation
Rank `1` is not present.

## Input Format

- First line: integer `n` — number of ranks.  
- Second line: `n` integers `arr[i]` — rank numbers.

## Output Format

- A single integer — the smallest missing rank.

## Constraints

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
