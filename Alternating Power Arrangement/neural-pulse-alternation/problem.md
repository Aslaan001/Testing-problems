## Title  
Neural Pulse Alternation  

## Slug  
neural-pulse-alternation  

## Difficulty  
Medium  

## Description  

A sequence of neurons fires with pulse intensities represented by nums.  
Before stimulation, you can reorder the firing order.  

Define total pulse output as:  

score = arr[0]^2 - arr[1]^2 + arr[2]^2 - arr[3]^2 + ...  

Find the arrangement that yields the maximum pulse output.  


## Examples  

### 1  

#### Input  
4  
1 2 3 4  

#### Output  
22  

#### Explanation  
Ordering [3, 1, 4, 2] gives  
3^2 - 1^2 + 4^2 - 2^2 = 9 - 1 + 16 - 4 = 20.  


### 2  

#### Input  
3  
-1 -2 -3  

#### Output  
14  

#### Explanation  
Reorder [-3, -2, -1] gives  
9 - 4 + 1 = 6.  


## Input Format  

- The first line contains integer n.  
- The second line contains n integers representing neural pulses.  


## Output Format  

Print maximum pulse output possible.  


## Constraints  

1 ≤ n ≤ 100000  
-40000 ≤ nums[i] ≤ 40000  


## Time Limit  

1 second  

## Memory Limit  

512 MB  


## Tags  

arrays, sorting.
