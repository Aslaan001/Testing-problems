## Title  
Mirror Energy Alignment  

## Slug  
mirror-energy-alignment  

## Difficulty  
Medium  

## Description  

A scientist is experimenting with energy mirrors that reflect power values represented by nums.  
You can rearrange their alignment to maximize the alternating reflection output.  

The reflection score is defined as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the mirror arrangement that yields the maximum reflection score.  


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
-1 -3 2 3  

#### Output  
20  

#### Explanation  
[-3, -1, 2, 3] → 9 - 1 + 4 - 9 = 3.  


## Input Format  

- The first line contains integer n.  
- The second line contains n integers representing mirror energies.  


## Output Format  

Print the maximum alternating reflection energy possible.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
