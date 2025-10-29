## Title

Unique Student ID

## Slug

unique-student-id

## Difficulty

Medium

## Description

A classroom record contains student IDs for each attendance.  
Some students attended multiple times.  

Find the `index of the first student` who attended only once.  

Return `-1` if no such student exists.

## Examples

### 1

#### Input

6  
2 3 5 3 2 7

#### Output
2

#### Explanation

Student 5 attended once → index 2.

### 2

#### Input

5  
1 1 2 2 3

#### Output
4

#### Explanation

Student 3 is unique → index 4.

## Input Format  

- First line: integer `n` — number of attendance entries.  
- Second line: `n` integers `arr[i]` — student IDs.

## Output Format  

- A single integer — index of first unique student, or `-1`.

## Constraints  

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
