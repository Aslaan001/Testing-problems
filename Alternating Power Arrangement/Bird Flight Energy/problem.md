## Title  
Bird Flight Energy  

## Slug  
bird-flight-energy  

## Difficulty  
Medium  

## Description  

Each bird in a flock has an energy level given by nums.  
You can rearrange their flying order to maximize the alternating flight energy.  

The formula for energy difference is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the order that produces the greatest possible energy.  


## Examples  

### 1  

#### Input  
3  
2 1 4  

#### Output  
19  

#### Explanation  
[2, 1, 4] → 4 - 1 + 16 = 19.  


### 2  

#### Input  
5  
-3 -2 1 2 3  

#### Output  
29  

#### Explanation  
[-3, -2, 1, 2, 3] → 9 - 4 + 1 - 4 + 9 = 11.  


## Input Format  

- The first line contains integer n.  
- The second line contains n integers representing flight energies.  


## Output Format  

Print a single integer — the maximum alternating flight energy.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
