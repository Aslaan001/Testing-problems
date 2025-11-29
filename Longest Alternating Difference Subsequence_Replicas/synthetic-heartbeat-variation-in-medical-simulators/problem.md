## Title
Synthetic Heartbeat Variation In Medical Simulators

## Slug
synthetic-heartbeat-variation-in-medical-simulators

## Difficulty
Medium

## Description
You are analyzing a sequence of synthetic heartbeat variation in medical simulators. A subsequence is alternating-difference if the sign of consecutive differences strictly alternates between positive and negative. Sequences of length 1 or any two distinct values are always alternating. Your task is to find the maximum length of such a subsequence.



### 1

#### Input
6  
1 7 4 9 2 5

#### Output
6

#### Explanation
The full sequence already alternates in sign.

### 2

#### Input
10  
1 17 5 10 13 15 10 5 16 8

#### Output
7

#### Explanation
One valid longest subsequence is:  
1, 17, 10, 13, 10, 16, 8

### 3

#### Input
9  
1 2 3 4 5 6 7 8 9

#### Output
2

#### Explanation
Differences never change sign. Any two increasing values form a valid subsequence.

## Input Format

- The first line contains an integer n.  
- The second line contains n space-separated integers.

## Output Format

Return a single integer: the length of the longest alternating-difference subsequence.

## Constraints

1 ≤ n ≤ 1000  
0 ≤ nums[i] ≤ 1000

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
array, greedy, dynamic-programming

## Company
hackwithinfy
