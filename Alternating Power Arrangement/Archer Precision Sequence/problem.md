## Title  
Archer Precision Sequence  

## Slug  
archer-precision-sequence  

## Difficulty  
Medium  

## Description  

A group of archers has precision values given by nums.  
You can rearrange their shooting order to maximize alternating accuracy strength.  

The accuracy metric is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Determine the optimal arrangement.  


## Examples  

### 1  

#### Input  
3  
1 3 2  

#### Output  
12  

#### Explanation  
[2, 1, 3] → 4 - 1 + 9 = 12.  


### 2  

#### Input  
4  
-2 -1 1 2  

#### Output  
14  

#### Explanation  
[-2, -1, 1, 2] → 4 - 1 + 1 - 4 = 0.  


## Input Format  

- First line: n  
- Second line: n integers (precision values).  


## Output Format  

Print the maximum alternating precision score.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
