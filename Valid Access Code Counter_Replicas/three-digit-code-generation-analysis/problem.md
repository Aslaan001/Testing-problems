## Title
Three Digit Code Generation Analysis

## Slug
three-digit-code-generation-analysis

## Difficulty  
Easy  

## Description

In a enterprise security validation service, numeric access codes are generated from a predefined collection of available digits.

Each access code must consist of exactly three digits and represent an even numerical value. Codes that begin with zero are considered invalid and must be excluded from the count.

Digits may be reused only up to the number of times they appear in the provided collection. This restriction ensures that generated codes accurately reflect real availability constraints within the system.

The objective is to compute the total number of distinct valid access codes that can be formed while respecting all digit usage rules and formatting requirements.
## Examples  

### 1  

#### Input  
4  
5 2 3 1  

#### Output  
2  

#### Explanation  

- The adjacent pair (3, 1) has the minimum sum of 4 → array becomes [5, 2, 4]  
- The adjacent pair (2, 4) has the minimum sum of 6 → array becomes [5, 6]  
- The array is now non-decreasing after 2 operations  

### 2  

#### Input  
3  
1 2 2  

#### Output  
0  

#### Explanation  

The array is already non-decreasing, so no operations are needed.

## Input Format  

- The first line contains an integer n — the length of the array  
- The second line contains n space-separated integers representing the array values  

## Output Format  

Return a single integer representing the minimum number of merge operations required.

## Constraints  

1 ≤ n ≤ 50  
-1000 ≤ nums[i] ≤ 1000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

queue.