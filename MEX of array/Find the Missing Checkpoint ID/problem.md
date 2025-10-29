## Title

Find the Missing Checkpoint ID

## Slug

find-missing-checkpoint-id

## Difficulty

Easy

## Description

A robot travels through checkpoints labeled with IDs starting from 0.  
Some checkpoints were skipped.  

Find the first checkpoint ID that was **not visited** — the `MEX` of the list.

## Examples

### 1

#### Input

6  
0 1 2 4 5 6

#### Output
3

#### Explanation
Checkpoint `3` was skipped.

### 2

#### Input

4  
0 1 2 3

#### Output
4

#### Explanation
Next missing checkpoint is `4`.

## Input Format

- First line: integer `n` — number of visited checkpoints.  
- Second line: `n` integers `arr[i]` — checkpoint IDs.

## Output Format

- A single integer — the missing checkpoint ID.

## Constraints

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
