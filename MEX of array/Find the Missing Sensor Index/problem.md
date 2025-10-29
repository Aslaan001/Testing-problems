## Title

Find the Missing Sensor Index

## Slug

find-missing-sensor-index

## Difficulty

Easy

## Description

A monitoring system assigns sensors indexes starting from 0.  
Some sensors failed to register.  

Given the list of working sensors, find the smallest sensor index missing — the `MEX` of the list.

## Examples

### 1

#### Input

5  
0 1 3 4 5

#### Output
2

#### Explanation
Sensor `2` is missing.

### 2

#### Input

4  
0 1 2 3

#### Output
4

#### Explanation
Next missing index is `4`.

## Input Format

- First line: integer `n` — number of working sensors.  
- Second line: `n` integers `arr[i]` — sensor indexes.

## Output Format

- A single integer — the missing sensor index.

## Constraints

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
