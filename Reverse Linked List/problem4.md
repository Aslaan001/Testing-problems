## Title  
Backtrack the Linked Chain  

## Slug  
backtrack-the-linked-chain  

## Difficulty  
Easy  

## Description  

A singly linked chain moves forward in one direction.  
You need to **backtrack the links** so that traversal happens from the end to the start.  

You are given the head of a linked list.  
Return the new head after completely reversing it.  

## Examples  

### 1  

#### Input  
4  
11 22 33 44  

#### Output  
44 33 22 11  

#### Explanation  
The order of nodes becomes reversed after adjusting the pointers.  

### 2  

#### Input  
2  
9 1  

#### Output  
1 9  

#### Explanation  
Reversing the list switches the direction of pointers.  

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
