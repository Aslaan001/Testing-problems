## Title
Alchemist's Transmutation Task

## Slug
alchemist-s-transmutation-task

## Difficulty
Medium

## Description
Alchemist is preparing a grand transmutation task using a alchemical formula tablet. The recipe requires him to consider every possible combination of consecutive elements he has. Each ingredient has a alchemical strength, represented by a positive integer.

For every contiguous group of elements, the weakest (minimum) ingredient determines the alchemical balance of that group. To complete the transmutation task, Alchemist needs to calculate the sum of the alchemical balances of all possible groups.

Since the number can grow very large, Alchemist only cares about the result modulo 10^9 + 7.

Your task is to help Alchemist compute this total so that his transmutation task becomes a success.

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