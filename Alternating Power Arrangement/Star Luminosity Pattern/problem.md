## Title  
Star Luminosity Pattern  

## Slug  
star-luminosity-pattern  

## Difficulty  
Medium  

## Description  

A galaxy has stars with varying luminosities given by nums.  
You can reorder the sequence to achieve the strongest alternating brightness pattern.  

Luminosity is measured as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the arrangement that maximizes this value.  


## Examples  

### 1  

#### Input  
4  
1 2 3 4  

#### Output  
22  

#### Explanation  
[3, 1, 4, 2] → 9 - 1 + 16 - 4 = 20.  


### 2  

#### Input  
3  
-3 -1 -2  

#### Output  
14  

#### Explanation  
[-3, -2, -1] → 9 - 4 + 1 = 6.  


## Input Format  

- The first line contains integer n.  
- The second line contains n integers representing star luminosities.  


## Output Format  

Print maximum alternating brightness value.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
