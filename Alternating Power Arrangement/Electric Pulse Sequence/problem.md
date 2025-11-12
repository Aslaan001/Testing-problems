## Title  
Electric Pulse Sequence  

## Slug  
electric-pulse-sequence  

## Difficulty  
Medium  

## Description  

A circuit receives electric pulses with strengths represented by nums.  
You can reorder the sequence of pulses to maximize the alternating current power.  

The total current is given by:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the arrangement with the highest alternating power.  


## Examples  

### 1  

#### Input  
3  
1 4 2  

#### Output  
19  

#### Explanation  
[2, 1, 4] → 4 - 1 + 16 = 19.  


### 2  

#### Input  
4  
-2 3 -1 1  

#### Output  
14  

#### Explanation  
[-2, -1, 1, 3] → 4 - 1 + 1 - 9 = -5.  


## Input Format  

- First line: integer n.  
- Second line: n integers representing pulse strengths.  


## Output Format  

Print the maximum alternating current power.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
