## Title

Inactive Channel Triples

## Slug

inactive-channel-triples

## Difficulty

Hard

## Description

In a system known as inactive channel triples, a collection of numeric signals is analyzed to detect compatible groupings.
Each signal is represented as a non-negative integer, and all possible ordered triples of signals are considered.

A triple is deemed valid if a specific bitwise interaction among the three signals results in a neutral state.
This interaction is evaluated using a bitwise operation applied simultaneously across all three values.

Your task is to count how many ordered triples satisfy this neutrality condition.
Return the total number of such valid combinations.

## Examples

### 1

#### Input

3  
2 1 3

#### Output
12

#### Explanation

There are `3 × 3 × 3 = 27` ordered triples.  
Among them, 12 triples produce a bitwise AND equal to zero.

### 2

#### Input

3  
0 0 0

#### Output

27

#### Explanation

Every triple results in `0 & 0 & 0 = 0`.  
So all 27 triples are valid.

## Input Format

- First line: integer `n` — number of elements.  
- Second line: `n` integers `nums[i]`.

## Output Format

- Return a single integer — the number of valid AND triples.

## Constraints

- 1 ≤ n ≤ 1000  
- 0 ≤ nums[i] < 2¹⁶  
- Result fits in 64-bit integer.

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

dynamic-programming
