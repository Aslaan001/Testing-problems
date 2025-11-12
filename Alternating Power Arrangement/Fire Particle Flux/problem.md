## Title  
Fire Particle Flux  

## Slug  
fire-particle-flux  

## Difficulty  
Medium  

## Description  

You are analyzing particles of fire, each with a flux value given by nums.  
By rearranging the particles, you can control the overall alternating thermal flux.  

The flux formula is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the maximum flux achievable.  


## Examples  

### 1  

#### Input  
3  
2 3 1  

#### Output  
12  

#### Explanation  
[2, 1, 3] → 4 - 1 + 9 = 12.  


### 2  

#### Input  
6  
-3 -2 -1 1 2 3  

#### Output  
36  

#### Explanation  
[-3, -1, -2, 1, 2, 3] → 9 - 1 + 4 - 1 + 4 - 9 = 6.  


## Input Format  

- n (number of particles)  
- followed by n integers (flux values).  


## Output Format  

Print the maximum alternating thermal flux.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
