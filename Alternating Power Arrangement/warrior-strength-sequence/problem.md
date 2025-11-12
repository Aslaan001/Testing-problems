## Title  
Warrior Strength Sequence  

## Slug  
warrior-strength-sequence  

## Difficulty  
Medium  

## Description  

A group of warriors each possess a strength value represented by an integer array nums.  
You can arrange them in any order before they face the trial.  

The trial’s total alternating strength is calculated as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the maximum alternating strength that can be achieved by reordering the warriors optimally.  


## Examples  

### 1  

#### Input  
3  
2 3 4  

#### Output  
20  

#### Explanation  
Arranging as [3, 2, 4] gives maximum power:  
3^2 - 2^2 + 4^2 = 9 - 4 + 16 = 21.  


### 2  

#### Input  
4  
1 -2 -3 2  

#### Output  
14  

#### Explanation  
Order [-3, -2, 1, 2] gives:  
9 - 4 + 1 - 4 = 2.  


## Input Format  

- The first line contains an integer n — number of warriors.  
- The second line contains n integers denoting their strengths.  


## Output Format  

Print the maximum alternating strength possible.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
