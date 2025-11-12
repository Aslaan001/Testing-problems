## Title  
Volcano Energy Burst  

## Slug  
volcano-energy-burst  

## Difficulty  
Medium  

## Description  

You are measuring volcanic eruptions, each with an intensity value given in nums.  
You can reorder the eruption records to achieve maximum alternating burst energy.  

The energy calculation is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the maximum possible eruption energy.  


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
-1 -3 2 3  

#### Output  
20  

#### Explanation  
[-3, -1, 2, 3] → 9 - 1 + 4 - 9 = 3.  


## Input Format  

- First line: n  
- Second line: n integers representing intensities.  


## Output Format  

Print maximum alternating eruption energy.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
