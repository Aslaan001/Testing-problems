## Title

Incremental Load Crest Detection

## Slug

incremental-load-crest-detection

## Difficulty

Hard

## Description

A live analytics module tracks infrastructure demand by continuously shifting a fixed-size
evaluation interval across incoming data points. The module is responsible for reporting the
highest reading visible within the interval before advancing it. This design supports fast     peak
detection while avoiding repeated full-range computations.

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


