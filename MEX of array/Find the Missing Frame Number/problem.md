## Title

Find the Missing Frame Number

## Slug

find-missing-frame-number

## Difficulty

Easy

## Description

In a video processing system, each frame is labeled with a non-negative integer starting from 0.  
Some frames were corrupted and lost during transmission.  

Given the list of successfully received frame numbers, find the smallest frame number that is missing — the `MEX` of the list.

## Examples

### 1

#### Input

6  
0 1 3 4 5 6

#### Output
2

#### Explanation
Frames 0, 1, 3, 4, 5, 6 are received.  
Frame number `2` is missing.

### 2

#### Input

4  
0 1 2 3

#### Output
4

#### Explanation
Frames 0–3 exist.  
The next missing frame is `4`.

## Input Format

- First line: integer `n` — number of received frames.  
- Second line: `n` integers `arr[i]` — frame numbers.

## Output Format

- A single integer — the missing frame number.

## Constraints

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
