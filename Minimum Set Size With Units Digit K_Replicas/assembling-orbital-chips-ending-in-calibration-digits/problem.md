## Title
Assembling Orbital Chips Ending In Calibration Digits

## Slug
assembling-orbital-chips-ending-in-calibration-digits

## Difficulty
Medium

## Description
You are constructing a collection of values representing assembling orbital chips ending in calibration digits. Each chosen number must end with digit k, and their total must equal num. Repetition is allowed, and an empty set sums to 0. Your task is to determine the minimum number of such numbers needed, or return -1 if impossible.



### 1
#### Input
58 9

#### Output
2

#### Explanation
Valid sets include:  
[9, 49]  
[19, 39]  
Both sum to 58, and the minimum size is 2.

### 2
#### Input
37 2

#### Output
-1

#### Explanation
No combination of numbers ending with digit 2 can sum to 37.

### 3
#### Input
0 7

#### Output
0

#### Explanation
The empty set has sum 0.

## Input Format
- A single line with two integers `num` and `k`.

## Output Format
Return a single integer — the minimum size of the set, or `-1` if no valid set exists.

## Constraints
0 ≤ num ≤ 3000  
0 ≤ k ≤ 9

## Time Limit
1 second

## Memory Limit
512 MB

## Tags
math, greedy, modular-arithmetic

## Company
hackwithinfy
