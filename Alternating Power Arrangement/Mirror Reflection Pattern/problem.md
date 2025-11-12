## Title  
Mirror Reflection Pattern  

## Slug  
mirror-reflection-pattern  

## Difficulty  
Medium  

## Description  

Each mirror has a reflection intensity represented by nums.  
You can reorder them to create the strongest alternating reflection pattern.  

Reflection strength is computed as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the maximum reflection pattern score.  


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
-3 -2 2 1  

#### Output  
18  

#### Explanation  
[-3, -2, 1, 2] → 9 - 4 + 1 - 4 = 2.  


## Input Format  

- First line: n  
- Second line: n integers for reflection powers.  


## Output Format  

Print the maximum alternating reflection score.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
