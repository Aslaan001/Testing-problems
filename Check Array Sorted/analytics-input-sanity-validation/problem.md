## Title

Analytics Input Sanity Validation

## Slug

analytics-input-sanity-validation

## Description

Analytics platforms perform initial sanity checks on input datasets before executing complex
computations. One of these checks ensures that numerical arrays are sorted in non-decreasing order.
Given an array of integers, perform this validation and report the outcome. This step helps prevent
unnecessary computation on malformed data.

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

