## Title  
Check Customer Queue Pattern  

## Slug  
check-customer-queue-pattern  

## Difficulty  
Easy  

## Description  

A store records customer IDs in a queue represented as a linked list.  
Determine if the queue follows a `palindromic` entry pattern.  

Return `true` if it does, otherwise `false`.  

## Examples  

### 1  

#### Input  
5  
4 6 8 6 4  

#### Output  
true  

#### Explanation  
The queue order is identical from both ends.  

### 2  

#### Input  
4  
2 5 6 7  

#### Output  
false  

#### Explanation  
The reversed queue differs.  

## Input Format  
- First line: integer n — number of customers.  
- Second line: customer IDs.  

## Output Format  
Return `true` if palindromic, otherwise `false`.  

## Constraints  
- 1 ≤ n ≤ 1000  
- 0 ≤ node.val ≤ 1000  

## Time Limit  
1 second  

## Memory Limit  
512 MB  

## Tags  
linked-list
