## Title  
Reverse the Chain of Command  

## Slug  
reverse-chain-of-command  

## Difficulty  
Easy  

## Description  

A company's chain of command is represented as a singly linked list where each node points to the next subordinate.  
Due to an organizational shuffle, you must reverse the chain so the junior-most employee becomes the head of the list.  

You are given the head of the linked list representing the chain.  
Return the new head of the list after reversing it.  


## Examples  

### 1  

#### Input  
5  
10 20 30 40 50  

#### Output  
50 40 30 20 10  

#### Explanation  
After reversing, the chain is reversed and the junior-most (50) becomes the head.  


### 2  

#### Input  
4  
5 10 15 20  

#### Output  
20 15 10 5  

#### Explanation  
The chain direction is reversed: 20 → 15 → 10 → 5.  


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
