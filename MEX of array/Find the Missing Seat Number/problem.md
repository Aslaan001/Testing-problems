## Title

Find the Missing Seat Number

## Slug

find-missing-seat-number

## Difficulty

Easy

## Description

A theater has seats numbered starting from 0.  
You have a list of occupied seat numbers.  

Your task is to find the smallest seat number that is **not** yet occupied — the `MEX` of the seat numbers.

## Examples

### 1

#### Input

5  
0 1 3 4 5

#### Output
2

#### Explanation
Seats 0, 1, 3, 4, 5 are occupied.  
The first free seat is number `2`.

### 2

#### Input

4  
1 2 3 0

#### Output
4

#### Explanation
Seats 0 to 3 are taken.  
The next available seat is `4`.

## Input Format

- First line: integer `n` — number of occupied seats.  
- Second line: `n` integers `arr[i]` — seat numbers.

## Output Format

- A single integer — the smallest free seat number.

## Constraints

- 1 ≤ n ≤ 10⁴  
- -10⁹ ≤ arr[i] ≤ 10⁹    

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays .
