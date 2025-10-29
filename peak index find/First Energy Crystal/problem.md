## Title

First Energy Crystal

## Slug

first-energy-crystal

## Difficulty

Medium

## Description

You are studying a row of glowing crystals represented by energy levels in an array.  
Find the first crystal whose energy level is greater than the sum of all before and after it.

Find the smallest index i such that:

- Sum before i < arr[i]  
- Sum after i < arr[i]

If no such crystal exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Crystal 1 has the strongest glow.

### 2

#### Input
5
3 2 4 2 1

#### Output
-1

#### Explanation
No crystal with dominant energy.

## Input Format
- First line: integer n — number of crystals.  
- Second line: n integers — energy levels.

## Output Format
- One integer — the first crystal index or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
