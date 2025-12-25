## Title

Streaming Interval Maximum Engine

## Slug

streaming-interval-maximum-engine

## Difficulty

Hard

## Description

A monitoring workflow processes time-indexed load metrics by applying a fixed-width frame     that
advances stepwise across the sequence. At every frame position, the workflow extracts the     most
critical value representing peak utilization. This mechanism avoids redundant scanning     and is
essential for real-time alerting systems operating under strict latency budgets.

## Examples

### 1

#### Input

8  
1 3 -1 -3 5 3 6 7  
3

#### Output

3 3 5 5 6 7

#### Explanation

The window positions and their maximum values are:

- [1, 3, -1] → 3  
- [3, -1, -3] → 3  
- [-1, -3, 5] → 5  
- [-3, 5, 3] → 5  
- [5, 3, 6] → 6  
- [3, 6, 7] → 7  

### 2

#### Input

1  
1  
1

#### Output

1

#### Explanation

There is only one window containing a single element, so the maximum value is the element itself.

## Input Format

- First line contains an integer n, the number of elements in the array.
- Second line contains n space-separated integers representing the array nums.
- Third line contains an integer k representing the window size.

## Output Format

- Return a sequence of integers representing the maximum value in each sliding window.

## Constraints

- 1 ≤ n ≤ 100000  
- -10000 ≤ nums[i] ≤ 10000  
- 1 ≤ k ≤ n

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

array

## Company


