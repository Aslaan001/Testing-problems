## Title

Robot Charge Pairs

## Slug

robot-charge-pairs

## Difficulty

Medium

## Description

A group of robots are being charged using energy pods. Each robot has a charge value stored in an array.  
You need to pair them so that the sum of charge values in every pair is perfectly divisible by `k`.

If possible, return `"YES"`, else `"NO"`.

### Example 1

#### Input
4  
9 7 5 3  
6

#### Output
YES

#### Explanation
Robots can be paired as `(9, 3)` and `(7, 5)` → both sums divisible by `6`.

### Example 2

#### Input
4  
92 75 65 48  
10

#### Output
YES

## Input Format

- First line: integer `n`.  
- Second line: robot charge values.  
- Third line: integer `k`.

## Output Format

- Return `"YES"` if valid pairing possible, otherwise `"NO"`.

## Constraints

- 1 ≤ n ≤ 10⁵  
- 1 ≤ arr[i] ≤ 10⁹  
- 1 ≤ k ≤ 10⁹  
- `n` is even  

## Time Limit

1 second  

## Memory Limit

512 MB  

## Tags

arrays, sorting.
