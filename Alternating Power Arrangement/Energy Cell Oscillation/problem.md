## Title  
Energy Cell Oscillation  

## Slug  
energy-cell-oscillation  

## Difficulty  
Medium  

## Description  

You are given a set of energy cells with integer power levels in an array nums.  
You can reorder these cells in any sequence before activation.  

When activated, the total oscillation energy is calculated as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Determine the maximum oscillation energy achievable through an optimal arrangement of the cells.  


## Examples  

### 1  

#### Input  
3  
1 2 3  

#### Output  
12  

#### Explanation  
Arranging as [2, 1, 3] gives maximum oscillation:  
2^2 - 1^2 + 3^2 = 12.  


### 2  

#### Input  
6  
1 -1 2 -2 3 -3  

#### Output  
16  

#### Explanation  
Optimal sequence: [-3, -1, -2, 1, 3, 2] gives  
9 - 1 + 4 - 1 + 9 - 4 = 16.  


## Input Format  

- The first line contains an integer n — the number of energy cells.  
- The second line contains n space-separated integers representing their power levels.  


## Output Format  

Print a single integer — the maximum oscillation energy possible.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
