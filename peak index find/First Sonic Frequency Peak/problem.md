## Title

First Sonic Frequency Peak

## Slug

first-sonic-frequency-peak

## Difficulty

Medium

## Description

A scientist is analyzing sound wave frequencies stored in an array.  
Each integer represents the amplitude of the sound at a specific moment.

Find the first frequency index i where:

- The sum of frequencies before i < arr[i]  
- The sum of frequencies after i < arr[i]

If no such frequency peak exists, return -1.

## Examples

### 1

#### Input
4
1 5 2 1

#### Output
1

#### Explanation
Frequency at index 1 dominates both sides.

### 2

#### Input
5
2 3 4 2 1

#### Output
-1

#### Explanation
No dominant sound wave found.

## Input Format
- First line: integer n — number of sound samples.  
- Second line: n integers — amplitude values.

## Output Format
- One integer — the first frequency peak index or -1.

## Constraints
1 ≤ n ≤ 10⁴  
0 ≤ arr[i] ≤ 10⁹  

## Time Limit
1 second  

## Memory Limit
512 MB  

## Tags
arrays
