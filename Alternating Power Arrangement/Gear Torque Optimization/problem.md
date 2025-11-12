## Title  
Gear Torque Optimization  

## Slug  
gear-torque-optimization  

## Difficulty  
Medium  

## Description  

You are designing a gear system where each gear has a torque value.  
You may rearrange them to balance rotational forces.  

Define the alternating torque as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the optimal arrangement that yields the maximum alternating torque.  


## Examples  

### 1  

#### Input  
3  
2 5 1  

#### Output  
28  

#### Explanation  
Order [5, 1, 2] gives:  
5^2 - 1^2 + 2^2 = 25 - 1 + 4 = 28.  


### 2  

#### Input  
4  
-2 0 3 -3  

#### Output  
22  

#### Explanation  
[-3, -2, 0, 3] gives 9 - 4 + 0 - 9 = -4.  


## Input Format  

- The first line contains integer n.  
- The second line contains n integers representing torque values.  


## Output Format  

Print a single integer — maximum alternating torque.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
