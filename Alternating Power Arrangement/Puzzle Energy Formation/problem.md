## Title  
Puzzle Energy Formation  

## Slug  
puzzle-energy-formation  

## Difficulty  
Medium  

## Description  

Each puzzle piece has an energy potential represented by nums.  
Arrange them to achieve the maximum alternating potential difference.  

The formula for potential energy is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Determine the best possible arrangement.  


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
2 1 3  

#### Output  
12  

#### Explanation  
[2, 1, 3] → 4 - 1 + 9 = 12.  


## Input Format  

- The first line contains n.  
- The second line contains n integers.  


## Output Format  

Print a single integer — maximum alternating potential.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
