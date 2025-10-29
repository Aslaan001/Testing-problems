## Title  
Reverse the Conveyor Belt  

## Slug  
reverse-conveyor-belt  

## Difficulty  
Easy  

## Description  

Items on a conveyor belt are represented as nodes in a singly linked list, moving from head to tail. The factory needs to reverse the processing direction so the item at the end becomes the first to be processed.  

Given the head of the linked list of item IDs, reverse the list and return its new head.  


## Examples  

### 1  

#### Input  
5  
10 20 30 40 50  

#### Output  
50 40 30 20 10  

#### Explanation  
The sequence of items is reversed.  


### 2  

#### Input  
4  
5 10 15 20  

#### Output  
20 15 10 5  

#### Explanation  
Direction of processing reversed.  


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
