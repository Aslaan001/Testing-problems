## Title

Sliding Window Load Extremum Tracker

## Slug

sliding-window-load-extremum-tracker

## Difficulty

Hard

## Description

A high-frequency telemetry system continuously samples numeric workload readings produced     by
infrastructure components. To extract meaningful insights from this stream, the system     inspects
only a limited span of recent samples at any time. As the inspection range advances     forward by
one unit, the system must immediately determine the highest observed value within     that range.
This enables rapid identification of short-lived saturation events without     recomputing
statistics from scratch for each movement.

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


