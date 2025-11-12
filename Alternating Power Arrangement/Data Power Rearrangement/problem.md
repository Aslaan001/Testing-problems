## Title  
Data Power Rearrangement  

## Slug  
data-power-rearrangement  

## Difficulty  
Medium  

## Description  

You are given an array nums representing raw data points.  
You can reorder them to maximize alternating computational power.  

The total power is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Compute the maximum achievable power.  


## Examples  

### 1  

#### Input  
3  
1 2 3  

#### Output  
12  

#### Explanation  
[2, 1, 3] → 4 - 1 + 9 = 12.  


### 2  

#### Input  
5  
-2 -1 0 1 2  

#### Output  
10  

#### Explanation  
[-2, -1, 0, 1, 2] → 4 - 1 + 0 - 1 + 4 = 6.  


## Input Format  

- n  
- n space-separated integers.  


## Output Format  

Print a single integer — maximum alternating data power.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
