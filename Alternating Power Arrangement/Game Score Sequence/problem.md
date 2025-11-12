## Title  
Game Score Sequence  

## Slug  
game-score-sequence  

## Difficulty  
Medium  

## Description  

A game awards score points given in nums.  
You can reorder levels to maximize the alternating total score difference.  

The formula is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the arrangement that gives the highest alternating score.  


## Examples  

### 1  

#### Input  
3  
2 3 1  

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
- The second line contains n integers (scores).  


## Output Format  

Print the maximum alternating score.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
