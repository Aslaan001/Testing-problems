## Title  

Print Delivery Stops  

## Slug  

print-delivery-stops  

## Difficulty  

Easy  

## Description  

A delivery truck travels through several stops in a fixed order.  
The stops are represented as a linked list where each node contains a stop number.  
Your task is to print all the stop numbers in the same order they are visited.  

Each number should be printed separated by a space.  



## Examples  

### Example 1  

#### Input  
5  
101 102 103 104 105  

#### Output  
101 102 103 104 105  

#### Explanation  
The delivery route is:  
`Start -> 101 -> 102 -> 103 -> 104 -> 105 -> NULL`.  

### Example 2  

#### Input  
3  
11 22 33  

#### Output  
11 22 33  

#### Explanation  
The truck stops in this order:  
`11 -> 22 -> 33 -> NULL`.  

## Input Format  

- First line: integer `n`, number of delivery stops.  
- Second line: `n` integers representing stop numbers.  

## Output Format  

Print all stop numbers separated by spaces.  

## Constraints  

- 1 ≤ n ≤ 1000  
- 0 ≤ stop number ≤ 1000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

linked-list, traversal, printing
