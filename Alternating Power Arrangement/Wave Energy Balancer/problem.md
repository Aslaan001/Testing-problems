## Title  
Wave Energy Balancer  

## Slug  
wave-energy-balancer  

## Difficulty  
Medium  

## Description  

You are analyzing ocean waves represented by an array nums, where each number indicates wave intensity.  
You can rearrange the wave sequence to achieve the highest alternating energy difference.  

Define the alternating wave power as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the arrangement that produces the maximum alternating wave energy.  


## Examples  

### 1  

#### Input  
3  
1 3 2  

#### Output  
12  

#### Explanation  
Ordering [2, 1, 3] yields  
2^2 - 1^2 + 3^2 = 4 - 1 + 9 = 12.  


### 2  

#### Input  
4  
-2 0 3 -1  

#### Output  
14  

#### Explanation  
[-2, -1, 0, 3] gives 4 - 1 + 0 - 9 = -6.  


## Input Format  

- The first line contains integer n.  
- The second line contains n integers representing wave intensities.  


## Output Format  

Print a single integer — maximum alternating wave energy.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
