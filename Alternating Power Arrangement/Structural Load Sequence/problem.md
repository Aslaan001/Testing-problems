## Title  
Structural Load Sequence  

## Slug  
structural-load-sequence  

## Difficulty  
Medium  

## Description  

A building has structural elements with load strengths given by nums.  
Rearrange them to achieve the maximum alternating structural efficiency.  

Efficiency score is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the order yielding the maximum alternating efficiency.  


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
4  
-3 -1 1 2  

#### Output  
20  

#### Explanation  
[-3, -1, 1, 2] → 9 - 1 + 1 - 4 = 5.  


## Input Format  

- n  
- n integers representing structural loads.  


## Output Format  

Print the maximum alternating efficiency.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
