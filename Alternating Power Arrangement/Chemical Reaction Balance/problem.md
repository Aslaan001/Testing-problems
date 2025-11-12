## Title  
Chemical Reaction Balance  

## Slug  
chemical-reaction-balance  

## Difficulty  
Medium  

## Description  

You have n chemicals, each with a reactivity level given by nums.  
By reordering them, you can control the reaction’s alternating intensity.  

The alternating reaction power is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the maximum intensity achievable.  


## Examples  

### 1  

#### Input  
3  
1 3 2  

#### Output  
12  

#### Explanation  
[2, 1, 3] → 4 - 1 + 9 = 12.  


### 2  

#### Input  
5  
-3 -1 0 1 2  

#### Output  
14  

#### Explanation  
[-3, -1, 0, 1, 2] → 9 - 1 + 0 - 1 + 4 = 11.  


## Input Format  

- n (number of chemicals)  
- n integers denoting reactivity levels.  


## Output Format  

Print the maximum alternating reaction intensity.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
