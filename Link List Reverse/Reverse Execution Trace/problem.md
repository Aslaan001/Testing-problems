## Title  
Reverse Execution Trace  

## Slug  
reverse-execution-trace  

## Difficulty  
Easy  

## Description  

An execution trace stores operations as nodes in a singly linked list from first to last. For debugging, you want to reverse the trace so the last operation is examined first.  

Given the head of the trace list, reverse it and return the new head.  


## Examples  

### 1  

#### Input  
5  
10 20 30 40 50  

#### Output  
50 40 30 20 10  

#### Explanation  
Trace reversed; last operation (50) appears first.  


### 2  

#### Input  
4  
5 10 15 20  

#### Output  
20 15 10 5  

#### Explanation  
Trace order reversed.  


## Input Format  
- First line: integer n — the number of nodes in the linked list.  
- Second line: n integers representing the data values of each node.  

Note: The nodes are provided as a linked list in order.  


## Output Format  
Return the new head of the reversed linked list, printed from head to tail.  


## Constraints  
- 1 ≤ n ≤ 1000  
- 0 ≤ node.val ≤ 1000  


## Time Limit  
1 second  

## Memory Limit  
512 MB  


## Tags  
linked-list, reverse, basic
