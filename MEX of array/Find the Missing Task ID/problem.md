## Title

Find the Missing Task ID

## Slug

find-missing-task-id

## Difficulty

Easy

## Description

A project management system assigns each task a unique non-negative ID.  
Some tasks are created, and their IDs are listed.  

Your job is to find the smallest ID that has **not yet** been assigned — the `MEX` of the list.

## Examples

### 1

#### Input

5  
0 1 3 4 5

#### Output
2

#### Explanation
Task IDs 0, 1, 3, 4, 5 exist.  
The smallest missing ID is `2`.

### 2

#### Input

4  
0 1 2 3

#### Output
4

#### Explanation
IDs 0–3 are assigned.  
Next ID should be `4`.

## Input Format

- First line: integer `n` — number of existing task IDs.  
- Second line: `n` integers `arr[i]` — task IDs.

## Output Format

- A single integer — the smallest missing task ID.

## Constraints

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
