## Title
Ice Sculptures

## Slug
ice-sculptures

## Difficulty

Medium

## Description
A row of ice sculptures stands along a straight line, each structure having a certain height.  
You want to choose two ice sculptures that, together with the ground, can hold the maximum possible stored energy between them.

The stored capacity is determined by the distance between the two ice sculptures and the height of the shorter one.  
You cannot tilt or alter the container formed by the two structures.

Given an array of integers representing the heights, return the maximum capacity achievable.

## Examples

### 1

#### Input

9  
1 8 6 2 5 4 8 3 7

#### Output  
49

#### Explanation

The two towers at indices 1 and 8 can store up to **49 units** of water.

### 2

#### Input

2  
1 1

#### Output  
1

#### Explanation

Both towers have the same height, forming a container of width 1 and height 1.

## Input Format  

- First line: integer `n` — number of towers.  
- Second line: `n` integers `height[i]`.

## Output Format  

- Return a single integer — the maximum amount of water that can be stored.

## Constraints  

- 2 ≤ n ≤ 10⁵  
- 0 ≤ height[i] ≤ 10⁴  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

two-pointers, greedy, arrays
