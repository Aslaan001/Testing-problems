## Title

First Data Spike

## Slug

first-data-spike

## Difficulty

Medium

## Description

A server records data usage at different times in an array.  
Each integer shows the amount of data transferred at that time.

Find the first data spike index i such that:

- The sum of data before i is less than arr[i].  
- The sum of data after i is less than arr[i].

If no spike is found, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Data usage peaks at index 1.

### 2

#### Input
5
2 3 3 2 1

#### Output
-1

#### Explanation
No significant data spike found.

## Input Format
- First line: integer n — number of data points.  
- Second line: n integers — data usage amounts.

## Output Format
- One integer — the first spike index or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
