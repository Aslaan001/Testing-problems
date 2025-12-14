## Title

Ancient Scroll Archive Division

## Slug

ancient-scroll-archive-division

## Difficulty

Hard

## Description

An archaeological archive stores scrolls labeled with numeric identifiers representing their era.
The curator must divide all scrolls into exactly k sealed chambers, each chamber holding the same number of scrolls.
To preserve authenticity, no chamber may contain two scrolls from the same era identifier.

The historical variance of a chamber is calculated as the maximum identifier minus the minimum identifier inside it.
The archive’s total variance is the sum of variances across all chambers.

Determine the minimum possible total variance achievable through proper distribution.
If the scrolls cannot be distributed under the given rules, return -1.

## Examples

### 1

#### Input
4 2
1 2 1 4  

#### Output  
4

#### Explanation

A valid distribution:  
- [1, 2] → incompatibility = 1  
- [1, 4] → incompatibility = 3  

Total = 4.


### 2

#### Input
6 3
5 3 3 6 3 3  

#### Output  
-1

#### Explanation

Each group must contain 2 elements, but duplicates make this impossible.  
Hence return -1.

## Input Format

- Integer array `nums`  
- Integer `k`  
- nums.length is divisible by k  
- 1 ≤ nums.length ≤ 16  
- 1 ≤ nums[i] ≤ nums.length

## Output Format

- Return the minimum total incompatibility, or -1 if no valid grouping exists.

## Constraints

- 1 ≤ nums.length ≤ 16  
- 1 ≤ k ≤ nums.length  
- nums.length % k == 0  
- Answer fits in 32-bit signed integer

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

DynamicProgramming
