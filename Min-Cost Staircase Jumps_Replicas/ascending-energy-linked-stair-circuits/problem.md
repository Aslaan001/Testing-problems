## Title
Ascending Energy-Linked Stair Circuits

## Slug
ascending-energy-linked-stair-circuits

## Difficulty
Medium

## Description
You are climbing a staircase represented by ascending energy-linked stair circuits. You may jump 1, 2, or 3 steps at a time, and each landing incurs a cost defined as costs[j] plus the square of the jump length. Starting from step 0, your goal is to reach step n with minimum total cost.



### 1

#### Input
4  
1 2 3 4

#### Output
13

#### Explanation
One optimal path is 0 → 1 → 2 → 4:

0 → 1 gives cost 1 + 1^2 = 2  
1 → 2 gives cost 2 + 1^2 = 3  
2 → 4 gives cost 4 + 2^2 = 8  

Total cost is 13.

### 2

#### Input
4  
5 1 6 2

#### Output
11

#### Explanation
One optimal path is 0 → 2 → 4:

0 → 2 gives cost 1 + 2^2 = 5  
2 → 4 gives cost 2 + 2^2 = 6  

Total cost is 11.

### 3

#### Input
3  
9 8 3

#### Output
12

#### Explanation
A direct jump is optimal:

0 → 3 gives cost 3 + 3^2 = 12

## Input Format

The first line contains the integer n.  
The second line contains n space-separated integers representing costs[1..n].

## Output Format

Return a single integer, the minimum total cost to reach step n.

## Constraints

1 ≤ n = costs.length ≤ 100000  
1 ≤ costs[i] ≤ 10000

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
dynamic-programming, greedy, staircase, optimization

## Company
hackwithinfy
