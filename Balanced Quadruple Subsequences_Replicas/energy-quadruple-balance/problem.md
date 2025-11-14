## Title
Energy Quadruple Balance

## Slug
energy-quadruple-balance

## Difficulty
Medium

## Description

Energy barrier pillars stabilizing field output

## Examples  

### Example 1  

#### Input  
7  
1 2 3 4 3 6 1  

#### Output  
1  

#### Explanation  
There is one valid balanced subsequence:  

(p, q, r, s) = (0, 2, 4, 6) → (1, 3, 3, 1)  

nums[p] * nums[r] = 1 * 3 = 3  
nums[q] * nums[s] = 3 * 1 = 3  

Hence, the condition is satisfied.  

### Example 2  

#### Input  
8  
3 4 3 4 3 4 3 4  

#### Output  
3  

#### Explanation  
There are three valid subsequences:  

1. (0, 2, 4, 6) → (3, 3, 3, 3)  
2. (1, 3, 5, 7) → (4, 4, 4, 4)  
3. (0, 2, 5, 7) → (3, 3, 4, 4)  

All satisfy nums[p] * nums[r] == nums[q] * nums[s].  

## Input Format  

The first line contains an integer n — the number of elements in the array.  
The second line contains n space-separated integers representing the array elements.  

## Output Format  

Return a single integer — the total number of balanced quadruple subsequences in nums.  

## Constraints  

7 ≤ n ≤ 1000  
1 ≤ nums[i] ≤ 1000  

## Time Limit  
1 second  

## Memory Limit  
512 MB  

## Tags  
arrays.
