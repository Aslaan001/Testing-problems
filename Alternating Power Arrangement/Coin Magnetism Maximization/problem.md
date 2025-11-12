## Title  
Coin Magnetism Maximization  

## Slug  
coin-magnetism-maximization  

## Difficulty  
Medium  

## Description  

Each coin in a vault has a magnetism value given by nums.  
You may rearrange the coins in any order.  

The alternating magnetism power is defined as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Your goal is to maximize the total magnetism score.  


## Examples  

### 1  

#### Input  
3  
1 5 4  

#### Output  
40  

#### Explanation  
Optimal arrangement [4, 1, 5] yields:  
4^2 - 1^2 + 5^2 = 16 - 1 + 25 = 40.  


### 2  

#### Input  
5  
-2 0 3 2 -3  

#### Output  
22  

#### Explanation  
Optimal sequence [-3, -2, 0, 2, 3] gives  
9 - 4 + 0 - 4 + 9 = 10.  


## Input Format  

- The first line contains integer n.  
- The second line contains n integers for the coins’ magnetism.  


## Output Format  

Print a single integer — maximum magnetism score possible.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
