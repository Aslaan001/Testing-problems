## Title
Galactic Energy Average

## Slug
galactic-energy-average

## Difficulty
Easy

## Description

In the Andromeda Cluster, each energy node emits varying amounts of power.  
Your mission is to identify `k` consecutive nodes that have the highest average energy output.

Return this maximum average, accurate up to 10⁻⁵.

## Examples

### 1
#### Input
6  
1 12 -5 -6 50 3  
4  

#### Output
12.75000  

#### Explanation
Nodes `[12, -5, -6, 50]` yield (12 - 5 - 6 + 50)/4 = 12.75

### 2
#### Input
1  
5  
1  

#### Output
5.00000  

#### Explanation
Only one node, average = 5.00000.

## Input Format
- First line: integer `n` — number of nodes.  
- Second line: `n` integers representing power levels.  
- Third line: integer `k`.

## Output Format
Return the maximum average power (accurate to 5 decimal places).

## Constraints
- 1 ≤ n ≤ 1e4  
- 1 ≤ k ≤ n  
- -10⁴ ≤ power[i] ≤ 10⁴  

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
sliding-window, arrays
