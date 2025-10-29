## Title  
Reverse Linked List of Orders  

## Slug  
reverse-linked-list-of-orders  

## Difficulty  
Easy  

## Description  

Customer orders are recorded as a singly linked list from oldest to newest. For processing in reverse, you need to flip the list so the newest order is processed first.  

Given the head of the orders list, reverse it and return the new head.  


## Examples  

### 1  

#### Input  
5  
10 20 30 40 50  

#### Output  
50 40 30 20 10  

#### Explanation  
Orders reversed to process newest first.  


### 2  

#### Input  
4  
5 10 15 20  

#### Output  
20 15 10 5  

#### Explanation  
Order list reversed.  


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
