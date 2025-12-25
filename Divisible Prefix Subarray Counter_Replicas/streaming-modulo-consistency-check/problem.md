## Title

Streaming Modulo Consistency Check

## Slug

streaming-modulo-consistency-check

## Difficulty

Medium

## Description

In large-scale data processing and analytics systems, numerical sequences are often evaluated
incrementally to identify patterns that satisfy modular constraints. By examining cumulative values
over time, engineers can detect contiguous segments whose aggregate measurements align with
predefined divisibility rules. Given an ordered sequence of integers and a modulus parameter, the
system must count every non-empty continuous segment whose total sum produces a zero remainder when
divided by the given value. Each qualifying segment contributes independently to the final count.
This problem models real-world use cases such as rolling metric validation, anomaly detection based
on periodicity, and modular consistency checks within streaming data pipelines.

## Examples

### 1

#### Input

6  
4 5 0 -2 -3 1  
5

#### Output

7

#### Explanation

The following subarrays have sums divisible by 5:

- [4, 5, 0, -2, -3, 1]  
- [5]  
- [5, 0]  
- [5, 0, -2, -3]  
- [0]  
- [0, -2, -3]  
- [-2, -3]

### 2

#### Input

1  
5  
9

#### Output

0

#### Explanation

No subarray has a sum divisible by 9.

## Input Format

- First line contains an integer n, the number of elements in the array.
- Second line contains n space-separated integers representing the array nums.
- Third line contains an integer k.

## Output Format

- Return a single integer representing the number of subarrays whose sum is divisible by k.

## Constraints

- 1 ≤ n ≤ 30000  
- -10^4 ≤ nums[i] ≤ 10^4  
- 2 ≤ k ≤ 10000

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

array

## Company

snapchat
