## Title
Celestial Plateau Bars

## Slug
celestial-plateau-bars

## Difficulty

Medium

## Description
After an environmental shift, water collects between celestial plateau bars of varying heights arranged in a straight line.  
Each unit has a non-negative height and a width of exactly 1 unit.

Your task is to determine how much water becomes trapped between these formations.  
Water accumulates only when a segment has taller boundaries on both its left and right sides.

Return the total amount of trapped water.

## Examples

### 1

#### Input

12  
0 1 0 2 1 0 1 3 2 1 2 1

#### Output  
6

#### Explanation

The elevation map represented by the heights traps `6 units` of rainwater.

### 2

#### Input

6  
4 2 0 3 2 5

#### Output  
9

#### Explanation

This configuration traps `9 units` of water.

## Input Format  

- First line: integer `n` — number of bars.  
- Second line: `n` integers `height[i]` — elevation of each bar.

## Output Format  

- Return a single integer — the total amount of trapped rainwater.

## Constraints  

- 1 ≤ n ≤ 2 × 10⁴  
- 0 ≤ height[i] ≤ 10⁵  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

arrays, two-pointers, stack, prefix-max
