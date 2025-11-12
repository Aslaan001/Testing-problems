## Title  
Brainwave Intensity Sequence  

## Slug  
brainwave-intensity-sequence  

## Difficulty  
Medium  

## Description  

You are studying brainwave readings represented by nums.  
You may rearrange them to maximize alternating brainwave intensity.  

The total intensity is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the maximum possible brainwave score.  


## Examples  

### 1  

#### Input  
3  
2 1 3  

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

- The first line contains n.  
- The second line contains n integers representing brainwave strengths.  


## Output Format  

Print the maximum alternating intensity.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
