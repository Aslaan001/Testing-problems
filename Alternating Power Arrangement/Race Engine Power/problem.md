## Title  
Race Engine Power  

## Slug  
race-engine-power  

## Difficulty  
Medium  

## Description  

Each engine in a racing vehicle has a power value in nums.  
Rearrange the engines to achieve the maximum alternating output power.  

Output power is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the arrangement giving the maximum alternating score.  


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
-3 -1 2 3  

#### Output  
20  

#### Explanation  
[-3, -1, 2, 3] → 9 - 1 + 4 - 9 = 3.  


## Input Format  

- The first line contains n.  
- The second line contains n integers (engine powers).  


## Output Format  

Print the maximum alternating power.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
