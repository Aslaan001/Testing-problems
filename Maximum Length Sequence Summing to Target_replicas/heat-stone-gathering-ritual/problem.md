## Title
Heat Stone Gathering Ritual

## Slug
heat-stone-gathering-ritual

## Difficulty  
Medium

## Description

In this scenario, In an ice fortress, gathering heat stones to match warming threshold. You must pick items in order so that their sum matches the target exactly, while maximizing how many items you can include.

## Examples  

### 1  

#### Input  
5  
1 2 3 4 5  
9  

#### Output  
3  

#### Explanation  
Possible selections summing to 9 include:  
- 1 + 3 + 5  
- 2 + 3 + 4  
The longest valid length is `3`.  


### 2  

#### Input  
6  
4 1 3 2 1 5  
7  

#### Output  
4  

#### Explanation  
A longest valid selection is:  
1 + 3 + 2 + 1 = 7  
Length = 4.  


### 3  

#### Input  
5  
1 1 5 4 5  
3  

#### Output  
-1  


## Input Format  

- The first line contains an integer `n` — the size of the array.  
- The second line contains `n` space-separated integers `nums[i]`.  
- The third line contains the integer `target`.  


## Output Format  

Return a single integer — the maximum length of any subsequence that sums to `target`, or `-1` if no such subsequence exists.  


## Constraints  

- 1 ≤ n ≤ 1000  
- 1 ≤ nums[i] ≤ 1000  
- 1 ≤ target ≤ 1000  


## Time Limit  

1 second  

## Memory Limit  

256 MB  


## Tags  

dynamic-programming, subsequence, knapsack
