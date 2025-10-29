## Title

First Peak Temperature

## Slug

first-peak-temperature

## Difficulty

Medium

## Description

You have recorded daily temperatures for several days in an array.  
Your task is to find the first day where the temperature is greater than the sum of all temperatures before and after it.

Find the smallest index i such that:

- The sum of temperatures before i is less than temp[i].  
- The sum of temperatures after i is less than temp[i].

If no such day exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
At day 1: left sum = 1 < 5, right sum = 3 < 5 → output 1.

### 2

#### Input
5
2 3 2 4 1

#### Output
-1

#### Explanation
No temperature satisfies the condition.

## Input Format
- First line: integer n — number of days.  
- Second line: n integers — temperature readings.

## Output Format
- One integer — the first peak temperature index or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
