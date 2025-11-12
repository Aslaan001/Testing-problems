## Title  
Satellite Signal Optimization  

## Slug  
satellite-signal-optimization  

## Difficulty  
Medium  

## Description  

A satellite transmits signals with strengths given in nums.  
You can rearrange the signals before transmission to achieve maximum alternating transmission power.  

The alternating transmission power is calculated as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the configuration that maximizes the signal power.  


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
6  
-2 -1 0 1 2 3  

#### Output  
28  

#### Explanation  
[-2, -1, 0, 1, 2, 3] → 4 - 1 + 0 - 1 + 4 - 9 = -3.  


## Input Format  

- First line: n  
- Second line: n integers representing signal strengths.  


## Output Format  

Print maximum alternating transmission power.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
