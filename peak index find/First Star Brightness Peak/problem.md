## Title

First Star Brightness Peak

## Slug

first-star-brightness-peak

## Difficulty

Medium

## Description

Astronomers are studying the brightness of a sequence of stars represented as an array.  
Each number indicates the brightness of a star in a linear arrangement.

Find the first star index i where:

- The total brightness before i is less than brightness[i].  
- The total brightness after i is also less than brightness[i].

If no such star exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Star at index 1 shines brighter than the combined brightness of others.

### 2

#### Input
5
3 4 2 1 3

#### Output
-1

#### Explanation
No star dominates both sides.

## Input Format
- First line: integer n — number of stars.  
- Second line: n integers — brightness levels.

## Output Format
- One integer — the first dominant star index or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
