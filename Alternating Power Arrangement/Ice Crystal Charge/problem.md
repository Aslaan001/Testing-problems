## Title  
Ice Crystal Charge  

## Slug  
ice-crystal-charge  

## Difficulty  
Medium  

## Description  

You are given an array nums representing charged ice crystals.  
You can rearrange them to achieve the maximum alternating cold charge.  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Determine the optimal order of the crystals.  


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
- The second line contains n integers (crystal charges).  


## Output Format  

Print maximum alternating cold charge.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
