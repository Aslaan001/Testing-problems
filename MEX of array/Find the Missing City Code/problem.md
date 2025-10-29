## Title

Find the Missing City Code

## Slug

find-missing-city-code

## Difficulty

Easy

## Description

Each city in a new transportation network is assigned a unique code starting from 0.  
Some cities have already been registered, and their codes are given.  

Your task is to find the smallest code number that hasn’t been assigned — the `MEX` of the given codes.

## Examples

### 1

#### Input

6  
0 1 2 4 5 6

#### Output
3

#### Explanation
Codes 0–2 and 4–6 exist.  
Code `3` is missing.

### 2

#### Input

3  
1 2 3

#### Output
0

#### Explanation
Code `0` is the first missing one.

## Input Format

- First line: integer `n` — number of city codes.  
- Second line: `n` integers `arr[i]` — city codes.

## Output Format

- A single integer — the smallest missing city code.

## Constraints

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
