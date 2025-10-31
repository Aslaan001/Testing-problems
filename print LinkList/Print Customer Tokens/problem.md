## Title  

Print Customer Tokens  

## Slug  

print-customer-tokens  

## Difficulty  

Easy  

## Description  

Customers are waiting in a service queue.  
Their tokens are stored in a linked list in the order they arrived.  
Your task is to print all token numbers in the same order.  

Each number should be printed separated by a space.  



## Examples  

### Example 1  

#### Input  
3  
15 27 39  

#### Output  
15 27 39  

#### Explanation  
The queue:  
`Front -> 15 -> 27 -> 39 -> NULL`.  

### Example 2  

#### Input  
5  
1 2 3 4 5  

#### Output  
1 2 3 4 5  

#### Explanation  
Tokens issued in order:  
`1 -> 2 -> 3 -> 4 -> 5 -> NULL`.  

## Input Format  

- First line: integer `n`, number of customers.  
- Second line: `n` integers representing token numbers.  

## Output Format  

Print all token numbers separated by spaces.  

## Constraints  

- 1 ≤ n ≤ 1000  
- 0 ≤ token number ≤ 1000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

linked-list, traversal, printing
