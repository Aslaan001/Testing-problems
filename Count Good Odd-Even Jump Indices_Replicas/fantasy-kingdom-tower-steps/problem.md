## Title
Fantasy Kingdom Tower Steps

## Slug
fantasy-kingdom-tower-steps

## Difficulty
Hard

## Description
You are traversing through the Fantasy Kingdom Tower Steps. Each position in your path is represented by an integer array arr of length n.

From any starting index i, you attempt a sequence of forward leaps.
The 1st, 3rd, 5th, ... leaps are odd-numbered, while the 2nd, 4th, 6th, ... leaps are even-numbered.

For every leap to index j > i, strict rules guide how the next point is chosen:

Odd-numbered leap:
Move to the index j for which arr[i] ≤ arr[j] and arr[j] is the smallest possible among all valid choices.
If multiple indices share the same value, choose the smallest j.

Even-numbered leap:
Move to the index j for which arr[i] ≥ arr[j] and arr[j] is the largest possible among all valid choices.
If multiple indices share the same value, choose the smallest j.

If no valid leap exists at any stage, the traversal ends.

A starting index is considered successful if it can eventually reach the final position (n − 1) after some sequence of leaps.

Your task is to count how many starting indices allow successful traversal of the trail.

## Examples

### 1

#### Input
5  
10 13 12 14 15

#### Output
2

### 2

#### Input
5  
2 3 1 1 4

#### Output
3

### 3

#### Input
5  
5 1 3 4 2

#### Output
3

## Input Format

The first line contains the integer n.  
The second line contains n integers representing arr.

## Output Format

Output a single integer — the number of good starting indices.

## Constraints

1 ≤ n ≤ 2 × 10⁴  
0 ≤ arr[i] < 10⁵

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
dynamic programming, monotonic stack, sorting, greedy

## Company
hackwithinfy
