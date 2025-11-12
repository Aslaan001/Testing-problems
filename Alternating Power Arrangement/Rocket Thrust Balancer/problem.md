## Title  
Rocket Thrust Balancer  

## Slug  
rocket-thrust-balancer  

## Difficulty  
Medium  

## Description  

You are designing a rocket with engines having thrust powers represented by nums.  
You can rearrange the engines before launch to maximize the alternating thrust difference.  

The thrust formula is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the engine arrangement that produces the maximum thrust balance score.  


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
4  
-1 -2 1 2  

#### Output  
14  

#### Explanation  
[-2, -1, 1, 2] → 4 - 1 + 1 - 4 = 0.  


## Input Format  

- The first line contains integer n.  
- The second line contains n integers representing thrust powers.  


## Output Format  

Print a single integer — maximum alternating thrust balance.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
