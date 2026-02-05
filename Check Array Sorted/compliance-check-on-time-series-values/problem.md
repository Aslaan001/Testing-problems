## Title

Compliance Check on Time-Series Values

## Slug

compliance-check-on-time-series-values

## Description

Time-series processing platforms enforce ordering constraints to guarantee efficient querying and
aggregation. You are given a sequence of integer values representing sampled data points. Verify
whether the sequence is sorted in non-decreasing order according to platform requirements. The
result determines whether the batch can be safely ingested.

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

