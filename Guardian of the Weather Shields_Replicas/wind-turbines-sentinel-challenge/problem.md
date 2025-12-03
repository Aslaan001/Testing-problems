## Title
Wind Turbines Sentinel Challenge

## Slug
wind-turbines-sentinel-challenge

## Difficulty
Hard

## Description
In a wind turbines system, n sites are arranged along a straight line, numbered from 1 to n.

For the next m days, forecasts warn of hazardous events.  
On day i, the affected interval of sites is [li, ri].  
A site remains unharmed if it is never impacted during the m days.

You control a mechanism capable of nullifying these events.  
You may choose k days on which all activity is fully cancelled.  
Your goal is to maximize the number of unharmed sites after selecting which k days to disable.

## Examples

### 1
#### Input
2 3 2  
1 2  
1 2  
1 1
#### Output
1

### 2
#### Input
5 3 2  
1 3  
2 4  
3 5
#### Output
2

### 3
#### Input
10 6 4  
1 5  
6 10  
2 2  
3 7  
5 8  
1 4
#### Output
6

## Input Format    
A line with integers n, m and k.  
Then m lines follow, each containing li and ri.

## Output Format
Return one integer representing the maximum number of safe outposts.

## Constraints 
1 ≤ n ≤ 200000  
2 ≤ m ≤ 200000  
2 ≤ k ≤ min(10, m)  
1 ≤ li ≤ ri ≤ n  
The total sum of all n values does not exceed 200000.  
The total sum of all m values does not exceed 200000.

## Time Limit
4000

## Memory Limit
1024

## Tags
combinatorics, hackwithinfy.

## Company
infosys
