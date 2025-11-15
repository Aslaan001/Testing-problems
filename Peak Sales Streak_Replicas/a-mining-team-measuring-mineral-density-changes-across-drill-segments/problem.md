## Title
A Mining team measuring mineral density changes across drill segments

## Slug
a-mining-team-measuring-mineral-density-changes-across-drill-segments

## Difficulty
Medium

## Description

a mining team measuring mineral density changes across drill segments. Each
value in the array represents the net change related to that theme. Your task is
to identify the most beneficial continuous segment, meaning the consecutive
portion where the cumulative value is the highest, and return that total.

## Examples

### 1

#### Input
11
3 -2 5 -1 4 -3 2 3 -2 4 -1

#### Output
13

#### Explanation
The best profitable streak is `[3, -2, 5, -1, 4, -3, 2, 3, -2, 4]`,
which gives a total profit of `13`.

### 2

#### Input
6
-5 -2 4 -1 2 3

#### Output
8

#### Explanation
The streak `[4, -1, 2, 3]` gives the maximum profit sum `8`.

### 3

#### Input
5
-2 -3 -1 -4 -6

#### Output
-1

#### Explanation
All days show losses, so the least loss day `-1` is the maximum possible total.

## Input Format

- First line contains an integer `n` — the number of days.
- Second line contains `n` space-separated integers representing the profit or loss for each day.

## Output Format

Return the `maximum total profit` possible in a continuous streak of days.

## Constraints

1 ≤ n ≤ 10⁵
−10⁴ ≤ nums[i] ≤ 10⁴

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays,kadane-algorithm
