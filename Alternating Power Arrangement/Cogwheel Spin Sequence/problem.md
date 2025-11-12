## Title  
Cogwheel Spin Sequence  

## Slug  
cogwheel-spin-sequence  

## Difficulty  
Medium  

## Description  

A machine has cogwheels, each with a spin rate represented by nums.  
You can rearrange them to maximize alternating rotational energy.  

The alternating spin energy is defined as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the highest achievable spin energy.  


## Examples  

### 1  

#### Input  
3  
2 3 4  

#### Output  
28  

#### Explanation  
[3, 2, 4] → 9 - 4 + 16 = 21.  


### 2  

#### Input  
4  
-3 -2 1 2  

#### Output  
18  

#### Explanation  
[-3, -2, 1, 2] → 9 - 4 + 1 - 4 = 2.  


## Input Format  

- First line: integer n.  
- Second line: n integers for spin rates.  


## Output Format  

Print the maximum alternating rotational energy.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
