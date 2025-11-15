## Title
Cyber Vault Node Sweep

## Slug
cyber-vault-node-sweep

## Difficulty  
Medium

## Description

Encrypted vault nodes arranged in a ring store digital credits. Accessing adjacent nodes triggers a firewall trap. Find the maximum safe credit extraction.

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
