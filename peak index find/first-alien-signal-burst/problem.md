## Title

First Alien Signal Burst

## Slug

first-alien-signal-burst

## Difficulty

Medium

## Description

An array represents the intensity of alien signals received over time.  
You must find the first signal burst that is stronger than all signals combined before and after it.

Find the smallest index i where:

- The sum before i is less than arr[i].  
- The sum after i is less than arr[i].

If no such burst exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Signal 1 is stronger than the combined before and after.

### 2

#### Input
5
1 2 3 2 1

#### Output
-1

#### Explanation
No signal burst satisfies the condition.

## Input Format
- First line: integer n — number of signals.  
- Second line: n integers — signal intensities.

## Output Format
- One integer — the index of the first signal burst or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
