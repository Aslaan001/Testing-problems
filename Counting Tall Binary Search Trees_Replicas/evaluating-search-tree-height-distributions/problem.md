## Title
Evaluating Search Tree Height Distributions

## Slug
evaluating-search-tree-height-distributions

## Difficulty
Hard

## Description
In large-scale software and data-intensive systems, evaluating search tree height distributions is a critical concern when evaluating performance guarantees.

Given a fixed set of uniquely ordered identifiers, system architects can construct multiple valid binary search tree configurations that respect strict ordering constraints.
Each configuration represents a different way the system might organize its indexed data in memory.

The height of such a structure directly impacts worst-case query latency, memory access patterns, and reliability under load.
Some configurations are shallow and efficient, while others are significantly deeper and represent potential performance risks.

For a given number of indexed elements, you are required to determine how many structurally distinct binary search trees result in a height that meets or exceeds a specified threshold.
Each valid structural arrangement must be counted independently, reflecting all possible system states that satisfy the constraints.


## Examples

### 1
#### Input
3 2  

#### Output
5  

#### Explanation
There are 5 distinct binary search trees with 3 nodes whose height is at least 2.

### 2
#### Input
3 3  

#### Output
4  

#### Explanation
Out of all possible binary search trees with 3 nodes, 4 have height at least 3.

## Input Format
- The input contains two space-separated integers n and h.

## Output Format
Return a single integer — the number of binary search trees with n nodes whose height is not less than h.

## Constraints
- 1 ≤ n ≤ 35  
- 1 ≤ h ≤ n  
- The answer does not exceed 9 × 10^18  

## Time Limit
1 second

## Memory Limit
64 megabytes

## Tags
maths, hackwithinfy

## Company
infosys
