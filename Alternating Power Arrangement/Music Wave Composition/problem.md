## Title  
Music Wave Composition  

## Slug  
music-wave-composition  

## Difficulty  
Medium  

## Description  

Each note in a melody has an amplitude represented by nums.  
By rearranging the notes, you can maximize the alternating harmony level.  

The harmony score is calculated as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Determine the rearrangement that produces the maximum harmony score.  


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

- The first line contains integer n.  
- The second line contains n integers representing amplitudes.  


## Output Format  

Print the maximum alternating harmony score.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
