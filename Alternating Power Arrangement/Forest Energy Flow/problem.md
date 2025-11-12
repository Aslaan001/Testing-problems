## Title  
Forest Energy Flow  

## Slug  
forest-energy-flow  

## Difficulty  
Medium  

## Description  

Each tree in a mystical forest emits energy represented by nums.  
You can reorder them to maximize the alternating forest energy balance.  

Energy balance is defined as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the arrangement that produces the maximum balance.  


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
5  
-2 -1 0 1 2  

#### Output  
10  

#### Explanation  
[-2, -1, 0, 1, 2] → 4 - 1 + 0 - 1 + 4 = 6.  


## Input Format  

- First line: integer n.  
- Second line: n integers representing energy levels.  


## Output Format  

Print the maximum alternating forest energy.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
