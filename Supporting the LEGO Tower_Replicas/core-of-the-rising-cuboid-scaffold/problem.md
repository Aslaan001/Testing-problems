## Title
Core of the Rising Cuboid Scaffold

## Slug
core-of-the-rising-cuboid-scaffold

## Difficulty
Hard

## Description
Core of the Rising Cuboid Scaffold describes a scenario where special target bricks must be suspended at height h along the x‑axis.

Each brick has a 2×2 base and height 1, perfectly axis‑aligned.  
A brick can rest on the ground or on another brick only if their faces overlap with positive area.

All required target bricks lie at coordinates (xᵢ, 0, h), strictly increasing in x and never intersecting.  
Additional support bricks may also be placed, but only at positions with y = 0, forming vertical or staggered stacks that create valid support paths from ground to height h.

Your goal is to determine the minimum number of such additional bricks needed to ensure every target brick at height h is fully supported while respecting all placement rules.

## Examples

### 1
#### Input
4 0
2 7 11 13
#### Output
0

### 2
#### Input
4 1
2 7 11 13

#### Output
3


## Input Format
A line with integers n and h  
A line with n integers x₁, x₂, …, xₙ in strictly increasing order

n is the number of purple bricks  
h is their common z-coordinate

Each purple brick has center at (xᵢ, 0, h).

## Output Format
Return the minimum number of additional support bricks needed.

## Constraints
1 ≤ n ≤ 300  
0 ≤ h ≤ 10⁹  
1 ≤ xᵢ ≤ 10⁹  
xᵢ < xᵢ₊₁

## Time Limit
2 seconds

## Memory Limit
256 megabytes

## Tags
geometry, hackwithinfy.

## Company
infosys
