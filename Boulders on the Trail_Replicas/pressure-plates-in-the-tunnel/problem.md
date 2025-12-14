## Title
Pressure Plates in the Tunnel

## Slug
pressure-plates-in-the-tunnel

## Difficulty
Hard

## Description
A line of entities is positioned along a narrow route in a scenario known as pressure plates in the tunnel.
Each entity starts with a certain strength value, and the route allows actions that affect a continuous segment at once.

Whenever an action is applied to a chosen segment, the strength of every affected entity is reduced by one.
If any entity’s strength drops to zero, it immediately resets to a fixed maximum value.

Your task is to determine the minimum number of segment-based actions required so that all entities end with their strength equal to the maximum possible value.
Each action may target any contiguous interval along the route.

## Examples

### 1
#### Input
4 3  
1 2 1 3

#### Output
2

#### Explanation
Throw on [1,3] → health becomes [3,1,3,3]  
Throw on [2,2] → health becomes [3,3,3,3]

### 2
#### Input
7 3  
1 2 3 1 3 2 1

#### Output
4

#### Explanation
One optimal sequence of intervals is [1,7], [2,6], [3,5], [4,4].

## Input Format
- The first line contains two integers n and k — the number of octopuses and the regeneration threshold.  
- The second line contains n integers a1, a2, …, an — the initial health values.

## Output Format
Return a single integer — the minimum number of boulders needed so that every octopus has health equal to k after all throws.

## Constraints 
1 ≤ n ≤ 2·10^5 (sum of n over all test cases ≤ 2·10^5)  
1 ≤ k ≤ 10^9  
1 ≤ ai ≤ k

## Time Limit
2 seconds

## Memory Limit
256 megabytes

## Tags
dynamic-programming, greedy, hackwithinfy

## Company
infosys
