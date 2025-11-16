## Title
Teacher's Syllabus Planning

## Slug
teacher-s-syllabus-planning

## Difficulty
Medium

## Description
Teacher is preparing a grand syllabus planning using a core lesson chart. The recipe requires him to consider every possible combination of consecutive topics he has. Each ingredient has a core strength, represented by a positive integer.

For every contiguous group of topics, the weakest (minimum) ingredient determines the core balance of that group. To complete the syllabus planning, Teacher needs to calculate the sum of the core balances of all possible groups.

Since the number can grow very large, Teacher only cares about the result modulo 10^9 + 7.

Your task is to help Teacher compute this total so that his syllabus planning becomes a success.

## Examples


### 1
#### Input
4
3 1 2 4

#### Output
17

#### Explanation

The subarrays are:

[3] → min = 3

[1] → min = 1

[2] → min = 2

[4] → min = 4

[3,1] → min = 1

[1,2] → min = 1

[2,4] → min = 2

[3,1,2] → min = 1

[1,2,4] → min = 1

[3,1,2,4] → min = 1

Sum = 17.

### 2
#### Input
5
11 81 94 43 3

#### Output
444

## Input Format

First line contains an integer n (size of the array).

Second line contains n integers, representing the magical strengths of the ingredients.

## Output Format

Return a single integer — the sum of the minimums of all contiguous subarrays, modulo 10^9 + 7.

## Constraints

- 1 ≤ n ≤ 3 × 10^4

- 1 ≤ arr[i] ≤ 3 × 10^4

## Time Limit

1 second

## Memory Limit

256 MB

## Tags

monotonic-stack, subarrays, dynamic-programming