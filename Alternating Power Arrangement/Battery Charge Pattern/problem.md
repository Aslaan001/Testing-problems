## Title  
Battery Charge Pattern  

## Slug  
battery-charge-pattern  

## Difficulty  
Medium  

## Description  

You are studying a set of batteries with charge capacities given in nums.  
You can reorder the charging sequence to get the highest alternating charge output.  

The alternating charge formula is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the maximum charge pattern achievable.  


## Examples  

### 1  

#### Input  
3  
1 2 4  

#### Output  
19  

#### Explanation  
Order [2, 1, 4] gives  
2^2 - 1^2 + 4^2 = 4 - 1 + 16 = 19.  


### 2  

#### Input  
5  
-2 2 -1 1 3  

#### Output  
21  

#### Explanation  
Optimal: [-2, -1, 1, 2, 3] → 4 - 1 + 1 - 4 + 9 = 9.  


## Input Format  

- The first line contains integer n.  
- The second line contains n integers representing charge values.  


## Output Format  

Print the maximum alternating charge.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
