## Title

Renewable Energy Clusters

## Slug

renewable-energy-clusters

## Difficulty

Hard

## Description

In a scenario involving renewable energy clusters, a collection of numbered units must be organized into exactly k groups.
Each group must contain the same number of units, and no group may include duplicate identifiers.

For any group, its internal spread is defined as the difference between the largest and smallest identifier it contains.
The total operational cost is calculated as the sum of these spreads across all groups.

Your objective is to arrange the units to achieve the minimum total cost while respecting all constraints.
If such an arrangement is impossible, return -1.

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
