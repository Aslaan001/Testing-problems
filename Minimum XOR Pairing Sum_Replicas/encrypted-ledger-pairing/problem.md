## Title

Encrypted Ledger Pairing

## Slug

encrypted-ledger-pairing

## Difficulty

Hard

## Description

In the process referred to as encrypted ledger pairing, two ordered collections of numeric signals must be carefully coordinated.
Each collection contains the same number of signals, and one collection may be reordered freely before pairing.

Once paired positionally, each signal interaction produces a cost determined by a bitwise interaction between the two values.
The overall system cost is defined as the sum of these interaction costs across all positions.

Your task is to determine the optimal reordering strategy that results in the smallest possible total cost.
Return the minimum achievable cost under these rules.

## Examples

### 1

#### Input
2
1 2  
2 3

#### Output
2

#### Explanation

One optimal rearrangement of nums2 is [3, 2].  
The XOR sum becomes:

(1 XOR 3) + (2 XOR 2) = 2 + 0 = 2.

### 2

#### Input
3
1 0 3  
5 3 4

#### Output
8

#### Explanation

An optimal rearrangement is nums2 = [5, 4, 3].  
The XOR sum is:

(1 XOR 5) + (0 XOR 4) + (3 XOR 3) = 4 + 4 + 0 = 8.

## Input Format

- Array nums1 of length n  
- Array nums2 of length n  

## Output Format

- Return the minimum total XOR sum achievable after reordering nums2.

## Constraints

- 1 ≤ n ≤ 14  
- n = nums1.length = nums2.length  
- 0 ≤ nums1[i], nums2[i] ≤ 10^7  
- Answer fits in 32-bit integer

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

dynamic-programming
