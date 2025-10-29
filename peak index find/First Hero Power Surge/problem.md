## Title

First Hero Power Surge

## Slug

first-hero-power-surge

## Difficulty

Medium

## Description

A group of heroes has gathered, each with a certain power level given in an array.  
You need to find the first hero whose power surpasses the total of all others before and after him.

Find the smallest index i such that:

- Sum of powers before i < power[i]  
- Sum of powers after i < power[i]

If no such hero exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Hero 1 has more power than the combined total before and after.

### 2

#### Input
5
1 3 2 3 1

#### Output
-1

#### Explanation
No hero dominates both sides.

## Input Format
- First line: integer n — number of heroes.  
- Second line: n integers — power levels.

## Output Format
- One integer — the index of the first dominant hero or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
