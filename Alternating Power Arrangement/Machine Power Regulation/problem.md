## Title  
Machine Power Regulation  

## Slug  
machine-power-regulation  

## Difficulty  
Medium  

## Description  

You are programming a machine with components having power ratings nums.  
You may reorder them to maximize the alternating energy efficiency.  

The efficiency score is defined as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the highest achievable efficiency.  


## Examples  

### 1  

#### Input  
4  
1 2 3 4  

#### Output  
22  

#### Explanation  
[3, 1, 4, 2] → 9 - 1 + 16 - 4 = 20.  


### 2  

#### Input  
3  
2 1 3  

#### Output  
12  

#### Explanation  
[2, 1, 3] → 4 - 1 + 9 = 12.  


## Input Format  

- n (number of components)  
- n integers for their power ratings.  


## Output Format  

Print the maximum alternating efficiency.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
