## Title  
Mountain Height Alternation  

## Slug  
mountain-height-alternation  

## Difficulty  
Medium  

## Description  

You are analyzing mountain heights given in nums.  
You may rearrange them in any order before calculating the alternating elevation index.  

The elevation score is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the maximum elevation index possible.  


## Examples  

### 1  

#### Input  
4  
1 3 2 4  

#### Output  
22  

#### Explanation  
[3, 1, 4, 2] → 9 - 1 + 16 - 4 = 20.  


### 2  

#### Input  
3  
-1 -2 -3  

#### Output  
14  

#### Explanation  
[-3, -2, -1] → 9 - 4 + 1 = 6.  


## Input Format  

- First line: integer n  
- Second line: n integers representing heights.  


## Output Format  

Print maximum alternating elevation score.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
