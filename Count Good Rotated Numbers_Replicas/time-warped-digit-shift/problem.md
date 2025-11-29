## Title
Time‑Warped Digit Shift

## Slug
time-warped-digit-shift

## Difficulty
Medium

## Description
You are examining numbers through the lens of the Time‑Warped Digit Shift. Each integer from 1 to n is evaluated by rotating every one of its digits by 180 degrees.

A number is considered good if the full rotation produces a valid transformed number, and that transformed number is different from the original.

Digits rotate as follows:
0, 1, and 8 remain the same after rotation.
2 and 5 transform into each other.
6 and 9 also transform into each other.
All other digits become invalid when rotated.

Each digit must be rotated — none may remain unchanged.

Your task is to count how many integers in the range [1, n] qualify as good under these rotation rules.

## Examples

### 1

#### Input
10

#### Output
4

#### Explanation
The good numbers are 2, 5, 6, 9.

### 2

#### Input
1

#### Output
0

### 3

#### Input
2

#### Output
1

## Input Format

The first line contains the integer n.

## Output Format

Return a single integer — the number of good rotated integers in [1, n].

## Constraints

1 ≤ n ≤ 10⁴

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
math, digit dp, enumeration, simulation

## Company
hackwithinfy
