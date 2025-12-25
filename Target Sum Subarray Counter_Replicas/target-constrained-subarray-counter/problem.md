## Title

Target-Constrained Subarray Counter

## Slug

target-constrained-subarray-counter

## Difficulty

Medium

## Description

In financial data platforms, transaction values accumulate over time and are frequently     reviewed
to identify periods where the net change equals a predefined amount. Rather than     examining
individual entries, analysts focus on continuous ranges of activity that together     produce an
exact balance. By scanning all possible contiguous intervals of a transaction list,     the service
must determine how many such intervals reach the specified target total.

## Examples

### 1

#### Input

3  
1 1 1  
2

#### Output

2

#### Explanation

The subarrays with sum equal to 2 are:

- [1, 1] (indices 0 to 1)  
- [1, 1] (indices 1 to 2)

### 2

#### Input

3  
1 2 3  
3

#### Output

2

#### Explanation

The valid subarrays are:

- [1, 2]  
- [3]

## Input Format

- First line contains an integer n, the number of elements in the array.
- Second line contains n space-separated integers representing the array nums.
- Third line contains an integer k, the target sum.

## Output Format

- Return a single integer representing the number of subarrays whose sum equals k.

## Constraints

- 1 ≤ n ≤ 20000  
- -1000 ≤ nums[i] ≤ 1000  
- -10⁷ ≤ k ≤ 10⁷

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

array

## Company

quora
