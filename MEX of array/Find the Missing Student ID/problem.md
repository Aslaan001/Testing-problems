## Title

Find the Missing Student ID

## Slug

find-missing-student-id

## Difficulty

Easy

## Description

Each student in a school is assigned a unique non-negative ID.  
You have a list of IDs of students currently enrolled.  

Your task is to find the smallest ID number that has not been assigned yet — the `MEX` of the list.

## Examples

### 1

#### Input

5  
0 1 2 4 6

#### Output
3

#### Explanation
IDs 0, 1, 2, 4, 6 are taken.  
The smallest missing ID is `3`.

### 2

#### Input

4  
0 1 2 3

#### Output
4

#### Explanation
IDs 0–3 exist.  
Next available ID is `4`.

## Input Format

- First line: integer `n` — number of assigned IDs.  
- Second line: `n` integers `arr[i]` — student IDs.

## Output Format

- A single integer — the smallest missing student ID.

## Constraints

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
