## Title

Exact Match Transaction Windows

## Slug

exact-match-transaction-windows

## Difficulty

Medium

## Description

In ledger analysis, it is often necessary to find exact matches between accumulated values     and
known targets. Given a array of signed transaction amounts, the analysis component must     examine
every contiguous portion of the array and count how many portions sum precisely to     the desired
value, regardless of length.

## Examples

### 1

#### Input

3  
1 1 1  
2

#### Output

2

#### Explanation

The subarrays with sum equal to 2 are:

- [1, 1] (indices 0 to 1)  
- [1, 1] (indices 1 to 2)

### 2

#### Input

3  
1 2 3  
3

#### Output

2

#### Explanation

The valid subarrays are:

- [1, 2]  
- [3]

## Input Format

- First line contains an integer n, the number of elements in the array.
- Second line contains n space-separated integers representing the array nums.
- Third line contains an integer k, the target sum.

## Output Format

- Return a single integer representing the number of subarrays whose sum equals k.

## Constraints

- 1 ≤ n ≤ 20000  
- -1000 ≤ nums[i] ≤ 1000  
- -10⁷ ≤ k ≤ 10⁷

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

array

## Company

quora
