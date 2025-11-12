## Title  
Frozen Core Sequence  

## Slug  
frozen-core-sequence  

## Difficulty  
Medium  

## Description  

Inside a glacier, you discover frozen cores with temperature levels given by nums.  
Reorder them to achieve the maximum alternating cold energy.  

The cold energy balance is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the configuration that yields the highest cold power.  


## Examples  

### 1  

#### Input  
3  
2 1 3  

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

- The first line contains n.  
- The second line contains n integers representing temperatures.  


## Output Format  

Print the maximum alternating cold energy.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
