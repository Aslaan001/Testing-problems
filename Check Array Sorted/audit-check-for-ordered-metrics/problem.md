## Title

Audit Check for Ordered Metrics

## Slug

audit-check-for-ordered-metrics

## Description

Modern monitoring platforms rely on continuously collected metrics to evaluate performance and
detect anomalies. You are provided with a list of integer measurements produced by an internal
metrics collector. Before these metrics can be archived and visualized, it must be verified that
they are arranged in non-decreasing order, as required by the aggregation engine. Your task is to
perform this verification efficiently and report whether the ordering constraint is satisfied.

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

