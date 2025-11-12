## Title  
Magic Wand Power Sequence  

## Slug  
magic-wand-power-sequence  

## Difficulty  
Medium  

## Description  

Each wand in your inventory has a power level given in nums.  
By reordering the wands, you can achieve the strongest alternating spell charge.  

The alternating charge is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the maximum possible spell power.  


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

- The first line contains integer n.  
- The second line contains n integers representing wand powers.  


## Output Format  

Print the maximum alternating spell power.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
