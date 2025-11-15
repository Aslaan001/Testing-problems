## Title  
Market Demand Index Trios  

## Slug  
market-demand-index-trios  

## Difficulty  
Medium  

## Description  

Economists track demand index values. Identify valid rising or falling trios.

## Examples  

### 1  

#### Input  
5  
2 5 3 4 1  

#### Output  
3  

#### Explanation  
The valid trios are:  
(2, 3, 4)  
(5, 4, 1)  
(5, 3, 1)  


### 2  

#### Input  
3  
2 1 3  

#### Output  
0  

#### Explanation  
No valid increasing or decreasing trio can be formed.  


### 3  

#### Input  
4  
1 2 3 4  

#### Output  
4  

#### Explanation  
The valid trios are all increasing:  
(1, 2, 3), (1, 2, 4), (1, 3, 4), (2, 3, 4).  

## Input Format  

The first line contains an integer `n` — the number of elements.  
The second line contains `n` space-separated integers representing the values.  

## Output Format  

Return a single integer — the total number of valid trios that can be formed.  

## Constraints  

3 ≤ n ≤ 1000  
1 ≤ value ≤ 100000  
All values are unique.  

## Time Limit  
1 second  

## Memory Limit  
256 MB  

## Tags  
arrays, counting, dynamic-programming, combinatorics
