## Title  
Invert List Pointers  

## Slug  
invert-list-pointers  

## Difficulty  
Easy  

## Description  

Each node points to its successor, forming a one-way chain.  
Your task is to **invert all pointers** so that the chain runs in the opposite direction.  

Given the head of a singly linked list,  
return the head of the list after reversing it.  

## Examples  

### 1  

#### Input  
5  
2 4 6 8 10  

#### Output  
10 8 6 4 2  

#### Explanation  
After inversion, the order is reversed from tail to head.  

### 2  

#### Input  
1  
42  

#### Output  
42  

#### Explanation  
A single-node list remains unchanged when reversed.  

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
