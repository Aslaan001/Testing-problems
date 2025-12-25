## Title

Rolling Resource Saturation Detector

## Slug

rolling-resource-saturation-detector

## Difficulty

Hard

## Description

An operational intelligence module evaluates server pressure using a moving observation
interval. Each interval reveals only a subset of the full measurement history, and the module
must report the dominant value inside that subset before shifting the interval forward. This
approach allows near-instantaneous detection of resource stress while maintaining linear
scalability across very large sequences.

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


