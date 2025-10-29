## Title

First Alpha Signal

## Slug

first-alpha-signal

## Difficulty

Medium

## Description

You are receiving signals from a distant satellite represented by an array of strengths.  
Each integer shows the signal strength at a given timestamp.

Find the first signal index i such that:

- The sum of all signal strengths before i is less than signal[i].  
- The sum of all signal strengths after i is also less than signal[i].

If no signal satisfies this condition, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Signal 1 stands out: before sum = 1, after sum = 3 → both less than 5.

### 2

#### Input
5
1 2 3 4 5

#### Output
-1

#### Explanation
No signal strong enough to dominate both sides.

## Input Format
- First line: integer n — number of signals.  
- Second line: n integers — signal strengths.

## Output Format
- One integer — the first alpha signal index or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
