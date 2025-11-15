## Title  
Balanced Rise Modification

## Slug  
balanced-rise-modification

## Difficulty  
Medium  

## Description  

You are given an integer array nums.

You may modify at most one element, adapting it to any value that fits the new storyline context. After this single modification, consider the longest segment where values never decrease as you move forward.

Your goal is to determine the maximum possible length of such a smooth, non‑decreasing subarray.

Return this maximum length.
## Examples  

### 1  

#### Input  
5  
1 2 3 1 2  

#### Output  
4  

#### Explanation  
By changing the element 1 at index 3 to 3, the array becomes:  
1 2 3 3 2  
The longest smooth subarray is 1 2 3 3, which has length 4.  


### 2  

#### Input  
5  
2 2 2 2 2  

#### Output  
5  

#### Explanation  
The array is already smooth.  
Therefore, the longest smooth subarray is the entire array of length 5.  


## Input Format  

- The first line contains an integer n — the number of elements in the array.  
- The second line contains n space-separated integers nums[i].  


## Output Format  

Return a single integer — the maximum length of a smooth subarray achievable with at most one change.  


## Constraints  

- 1 ≤ n ≤ 100000  
- -10^9 ≤ nums[i] ≤ 10^9  


## Time Limit  

1 second  

## Memory Limit  

256 MB  


## Tags  

arrays, greedy, subarray-analysis