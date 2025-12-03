## Title
Enigma of the Hidden Cell‑Forger

## Slug
enigma-of-the-hidden-cell-forger

## Difficulty
Hard

## Description
Enigma of the Hidden Cell‑Forger revolves around a mysterious device that processes n cells arranged in a line.  
Each cell begins white, holding an internal score of 0.

The device operates according to a concealed permutation p of 1…n.  
During each of the n operations, it first increments the score of the already‑blackened cell closest to the next target position, breaking ties toward the smaller index, and then it blackens the chosen cell.

When all operations complete, the resulting score array is observed—though some entries may be missing, marked as -1.  
Your task is to determine how many permutations p could have produced a final score array consistent with this partially known information, modulo 998244353.

## Examples

### 1
#### Input
3
-1 -1 1
#### Output
2

### 2
#### Input
3
-1 -1 -1
#### Output
6

### 3
#### Input
4
-1 2 -1 0
#### Output
4

## Input Format
A single integer n  
A line of n integers representing the array s, where si = -1 or 0 ≤ si < n.

## Output Format
Return the number of permutations that could generate a compatible score sequence.

## Constraints
2 ≤ n ≤ 100  
-1 ≤ si ≤ n − 1  
Sum of n² across all test cases ≤ 10000

## Time Limit
3000

## Memory Limit
512

## Tags
combinatorics,dp,hackwithinfy.

## Company
infosys
