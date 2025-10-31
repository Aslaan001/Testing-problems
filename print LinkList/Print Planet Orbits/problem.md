## Title  

Print Planet Orbits  

## Slug  

print-planet-orbits  

## Difficulty  

Easy  

## Description  

Planets orbit a star in a particular sequence represented by a linked list.  
Each node stores a planet’s orbit number.  
Your task is to print all orbit numbers in the correct order.  

Each number should be printed separated by a space.  



## Examples  

### Example 1  

#### Input  
4  
1 2 3 4  

#### Output  
1 2 3 4  

#### Explanation  
The orbit chain:  
`Sun -> 1 -> 2 -> 3 -> 4 -> NULL`.  

### Example 2  

#### Input  
5  
10 20 30 40 50  

#### Output  
10 20 30 40 50  

#### Explanation  
Planets orbit in order:  
`10 -> 20 -> 30 -> 40 -> 50 -> NULL`.  

## Input Format  

- First line: integer `n`, number of planets.  
- Second line: `n` integers representing orbit numbers.  

## Output Format  

Print all orbit numbers separated by spaces.  

## Constraints  

- 1 ≤ n ≤ 1000  
- 0 ≤ orbit number ≤ 1000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

linked-list, traversal, printing
