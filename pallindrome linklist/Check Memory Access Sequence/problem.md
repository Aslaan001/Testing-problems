## Title  
Check Memory Access Sequence  

## Slug  
check-memory-access-sequence  

## Difficulty  
Easy  

## Description  

A computer logs memory accesses in a linked list.  
Determine if the access pattern is `palindromic`, meaning it repeats in reverse order.  

Return `true` if it does, otherwise `false`.  

## Examples  

### 1  

#### Input  
5  
10 20 30 20 10  

#### Output  
true  

#### Explanation  
The access sequence mirrors itself.  

### 2  

#### Input  
4  
1 2 3 4  

#### Output  
false  

#### Explanation  
The reversed pattern differs.  

## Input Format  
- First line: integer n — number of accesses.  
- Second line: access IDs.  

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
