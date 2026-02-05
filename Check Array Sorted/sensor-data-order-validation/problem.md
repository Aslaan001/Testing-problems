## Title

Sensor Data Order Validation

## Slug

sensor-data-order-validation

## Description

Industrial sensor networks frequently transmit large volumes of numerical readings to centralized
processing units. Each batch of readings is expected to be ordered to simplify compression and
downstream analysis. Given an array of integers corresponding to sensor outputs, determine whether
the readings are already sorted in non-decreasing order. A correct validation result is critical for
maintaining the reliability of the monitoring pipeline.

## Difficulty

Easy

## Examples
### 1

#### Input
5
1 2 3 4 5

#### Output
YES

#### Explanation
The array `[1, 2, 3, 4, 5]` is already sorted in non-decreasing order.


### 2

#### Input
5
5 4 3 2 1

#### Output
NO

#### Explanation
The array is in decreasing order, so it is `not sorted`.

## Input Format
 
- First line contains an integer `n` — the number of elements in the array.  
- Second line contains `n` space-separated integers representing the array.

## Output Format

- Return `"YES"` if the array is sorted in non-decreasing order.  
- Otherwise, Return `"NO"`.

## Constraints

- 1 ≤ n ≤ 10⁶  
- 1 ≤ arr[i] ≤ 10⁶   

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

array, sorting.

