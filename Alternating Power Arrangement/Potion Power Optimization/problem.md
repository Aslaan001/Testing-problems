## Title  
Potion Power Optimization  

## Slug  
potion-power-optimization  

## Difficulty  
Medium  

## Description  

You are crafting potions with powers given in nums.  
You can mix them in any order to maximize alternating magical potency.  

Potency is measured by:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the optimal brewing sequence.  


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
- n integers representing potion powers.  


## Output Format  

Print the maximum alternating potency.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
