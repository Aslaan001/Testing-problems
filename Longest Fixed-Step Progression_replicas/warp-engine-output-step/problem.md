## Title
Warp Engine Output Step

## Slug
warp-engine-output-step

## Difficulty  
Medium

## Description

A warp engine records output intensities. A subsequence forms a legal pattern if intensity differences equal the fixed step. Identify the longest pattern.

## Examples  

### 1  

#### Input  
4  
1 2 3 4  
1

#### Output  
4

#### Explanation  
The sequence `[1, 2, 3, 4]` already follows a fixed step of `+1`.

### 2  

#### Input  
4  
1 3 5 7  
1

#### Output  
1

#### Explanation  
No two elements satisfy the required step difference.  
Any single element is a valid subsequence of length 1.

### 3  

#### Input  
9  
1 5 7 8 5 3 4 2 1  
-2

#### Output  
4

#### Explanation  
One longest valid subsequence is `[7, 5, 3, 1]`, where each step is `-2`.

## Input Format  

- The first line contains an integer n — the length of the array.
- The second line contains n integers representing nums.
- The third line contains the integer step.

## Output Format  

Return a single integer — the length of the longest valid progression subsequence.

## Constraints  

1 ≤ n ≤ 100000  
-10000 ≤ nums[i], step ≤ 10000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

dynamic programming, subsequence.
