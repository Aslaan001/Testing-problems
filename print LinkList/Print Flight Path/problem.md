## Title  

Print Flight Path  

## Slug  

print-flight-path  

## Difficulty  

Easy  

## Description  

A drone follows a predefined flight path represented as a linked list.  
Each node contains a waypoint number.  
Your task is to print all waypoints in the order they are visited.  

Each value should be printed separated by a space.  



## Examples  

### Example 1  

#### Input  
4  
101 102 103 104  

#### Output  
101 102 103 104  

#### Explanation  
Flight path:  
`Start -> 101 -> 102 -> 103 -> 104 -> NULL`.  

### Example 2  

#### Input  
3  
5 6 7  

#### Output  
5 6 7  

#### Explanation  
`Start -> 5 -> 6 -> 7 -> NULL`.  

## Input Format  

- First line: integer `n`, number of waypoints.  
- Second line: `n` integers representing waypoint numbers.  

## Output Format  

Print all waypoint numbers separated by spaces.  

## Constraints  

- 1 ≤ n ≤ 1000  
- 0 ≤ waypoint number ≤ 1000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

linked-list, traversal, printing
