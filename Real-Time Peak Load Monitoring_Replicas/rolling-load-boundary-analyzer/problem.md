## Title

Rolling Load Boundary Analyzer

## Slug

rolling-load-boundary-analyzer

## Difficulty

Hard

## Description

In performance diagnostics, recent measurements are often more relevant than historical     ones. A
sliding analysis frame is therefore applied to a numeric signal, revealing only a     constrained
segment at any moment. For each segment placement, the diagnostic module must     isolate the
maximum value efficiently to capture transient spikes as they occur.

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


