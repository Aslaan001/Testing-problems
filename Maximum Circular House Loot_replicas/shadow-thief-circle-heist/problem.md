## Title
Shadow Thief Circle Heist

## Slug
shadow-thief-circle-heist

## Difficulty  
Medium

## Description

In a city where houses form a closed ring, a stealthy thief plans a heist. Each house stores a certain amount of valuables, but triggering alarms in adjacent houses would expose the thief. Determine the maximum loot that can be taken without looting two neighboring houses.

## Examples  

### 1  

#### Input  
3  
2 3 2  

#### Output  
3  


### 2  

#### Input  
4  
1 2 3 1  

#### Output  
4  


### 3  

#### Input  
3  
1 2 3  

#### Output  
3  


## Input Format  

- The first line contains an integer n — the number of houses.  
- The second line contains n space-separated integers vals[i].  


## Output Format  

Return a single integer — the maximum total amount that can be collected.


## Constraints  

- 1 ≤ n ≤ 100  
- 0 ≤ vals[i] ≤ 1000  


## Time Limit  
1 second  

## Memory Limit  
256 MB  


## Tags  
dynamic-programming, circular-array, optimization
