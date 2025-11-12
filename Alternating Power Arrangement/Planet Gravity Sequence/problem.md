## Title  
Planet Gravity Sequence  

## Slug  
planet-gravity-sequence  

## Difficulty  
Medium  

## Description  

A galaxy contains planets with gravity fields represented by nums.  
You can reorder their orbit sequence to maximize alternating gravitational pull.  

The pull strength is given by:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the maximum alternating gravitational score.  


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
- The second line contains n integers.  


## Output Format  

Print the maximum alternating gravitational pull.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
