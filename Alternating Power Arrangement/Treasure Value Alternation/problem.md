## Title  
Treasure Value Alternation  

## Slug  
treasure-value-alternation  

## Difficulty  
Medium  

## Description  

You are sorting treasures with values represented by nums.  
Reorder them to maximize the alternating treasure score.  

The treasure score is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the arrangement with the maximum possible score.  


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
-1 -2 2 3  

#### Output  
20  

#### Explanation  
[-2, -1, 2, 3] → 4 - 1 + 4 - 9 = -2.  


## Input Format  

- n  
- n integers representing treasure values.  


## Output Format  

Print the maximum alternating treasure score.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
