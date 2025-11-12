## Title  
Mathematical Wave Function  

## Slug  
mathematical-wave-function  

## Difficulty  
Medium  

## Description  

You are given an integer array nums representing amplitudes of a mathematical wave.  
You can rearrange them to maximize the alternating squared amplitude.  

The wave strength is calculated as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the highest possible value of this function.  


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

Print the maximum alternating wave strength.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
