## Title
Void Pressure Logs

## Slug
void-pressure-logs

## Difficulty

Medium

## Description
In a specialized monitoring facility, analysts examine sequences of void pressure logs recorded along a linear array.  
Each reading is an integer (positive, negative, or zero).

You are given these readings and a divisor `k`.  
Your task is to determine how many non-empty continuous segments (subarrays) have a total void pressure logs sum divisible by `k`.

Return the total count of such subarrays.

A subarray is a contiguous part of the array.

## Examples

### 1

#### Input

6  
4 5 0 -2 -3 1  
5

#### Output  
7

#### Explanation

The following 7 subarrays have sums divisible by 5:

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

No subarray sum is divisible by 9.

## Input Format

- First line: integer `n` — number of readings.  
- Second line: `n` integers `nums[i]` — the energy readings.  
- Third line: integer `k`.

## Output Format

- Return a single integer — the number of non-empty subarrays whose sum is divisible by `k`.

## Constraints

- 1 ≤ n ≤ 3 × 10⁴  
- −10⁴ ≤ nums[i] ≤ 10⁴  
- 2 ≤ k ≤ 10⁴

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, prefix-sum, hashing
