## Title  
DNA Energy Alternation  

## Slug  
dna-energy-alternation  

## Difficulty  
Medium  

## Description  

Each DNA strand has an energy potential denoted by an integer in nums.  
You can rearrange the order of strands to produce maximum alternating gene energy.  

The total gene score is:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Determine the best arrangement for maximum total gene score.  


## Examples  

### 1  

#### Input  
3  
3 1 2  

#### Output  
12  

#### Explanation  
[2, 1, 3] → 4 - 1 + 9 = 12.  


### 2  

#### Input  
4  
-3 -2 1 2  

#### Output  
18  

#### Explanation  
[-3, -2, 1, 2] → 9 - 4 + 1 - 4 = 2.  


## Input Format  

- The first line contains n — number of strands.  
- The second line contains n integers — strand energies.  


## Output Format  

Print the maximum alternating gene energy.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
