## Title  
Crystal Resonance Maximizer  

## Slug  
crystal-resonance-maximizer  

## Difficulty  
Medium  

## Description  

You have a collection of magical crystals with resonance strengths given in nums.  
You can rearrange them before casting a spell.  

The alternating resonance power is calculated as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the maximum total resonance achievable.  


## Examples  

### 1  

#### Input  
3  
1 3 5  

#### Output  
33  

#### Explanation  
Arrange as [3, 1, 5] → 9 - 1 + 25 = 33.  


### 2  

#### Input  
4  
-1 -2 2 3  

#### Output  
18  

#### Explanation  
[-2, -1, 2, 3] → 4 - 1 + 4 - 9 = -2.  


## Input Format  

- First line: n  
- Second line: n integers representing crystal powers.  


## Output Format  

Print the maximum resonance power.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
