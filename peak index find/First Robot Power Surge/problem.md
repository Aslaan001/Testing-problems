## Title

First Robot Power Surge

## Slug

first-robot-power-surge

## Difficulty

Medium

## Description

You are testing a sequence of robots, each with a power reading given as an array.  
Find the first robot whose power output exceeds the total power of all robots before and after it.

Find index i where:

- Sum of power before i < arr[i]  
- Sum of power after i < arr[i]

If no such robot exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Robot 1 overpowers all others.

### 2

#### Input
5
1 3 3 2 1

#### Output
-1

#### Explanation
No dominant robot found.

## Input Format
- First line: integer n — number of robots.  
- Second line: n integers — power levels.

## Output Format
- One integer — the index of the first dominant robot or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
