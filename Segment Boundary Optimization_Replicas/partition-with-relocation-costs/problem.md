## Title
Partition with Relocation Costs

## Slug
partition-with-relocation-costs

## Difficulty
Hard

## Description
In a task referred to as partition with relocation costs, a sequence containing every identifier from 1 to n exactly once is arranged in a fixed order.
Each identifier has an associated cost that represents the expense of relocating it to a different segment.

The sequence must first be divided into two consecutive segments, with both segments initially containing at least one element.
After this division, elements may be moved across the boundary, and each such movement incurs its respective relocation cost.

The goal is to reach a configuration where all values in the left segment are strictly smaller than all values in the right segment.
If either segment becomes empty during the process, the requirement is considered automatically satisfied.

Determine the minimum total relocation cost needed to achieve this condition.

## Examples

### 1
#### Input
3  
3 1 2  
7 1 4  

#### Output
4  

#### Explanation
By choosing an appropriate initial split and transferring one element across the boundary, the required condition is achieved with a total cost of 4.

### 2
#### Input
4  
2 4 1 3  
5 9 8 3  

#### Output
3  

#### Explanation
A carefully planned split and a minimal set of transfers lead to a total cost of 3. 


## Input Format
- First line contains an integer n, the length of the sequence.
- Second line contains n integers representing a permutation of values from 1 to n.
- Third line contains n integers representing the relocation cost of each element.

## Output Format
- Return a single integer representing the minimum total cost required.

## Constraints
- 2 ≤ n ≤ 2 × 10^5
- Each value from 1 to n appears exactly once
- 1 ≤ relocation cost ≤ 10^9

## Time Limit
2 seconds

## Memory Limit
256 megabytes


## Tags
recursion, hackwithinfy

## Company
infosys
