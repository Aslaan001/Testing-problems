## Title  
Lightning Bolt Sequence  

## Slug  
lightning-bolt-sequence  

## Difficulty  
Medium  

## Description  

You are analyzing electric bolts, each having a charge level given by nums.  
You can reorder them to achieve the maximum alternating electric intensity.  

The alternating charge intensity is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the maximum possible value of this alternating intensity.  


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
-1 -3 2 3  

#### Output  
20  

#### Explanation  
[-3, -1, 2, 3] → 9 - 1 + 4 - 9 = 3.  


## Input Format  

- The first line contains integer n.  
- The second line contains n integers representing charges.  


## Output Format  

Print the maximum alternating electric intensity.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
