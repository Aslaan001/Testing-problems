## Title  
Flip the Node Chain  

## Slug  
flip-the-node-chain  

## Difficulty  
Easy  

## Description  

Picture a sequence of nodes connected in a single forward direction.  
Your goal is to **flip this sequence** so that the terminal node becomes the starting node.  

You are given the head of a singly linked list.  
Return the new head after reversing all the pointers in the list.  

## Examples  

### 1  

#### Input  
6  
3 1 4 1 5 9  

#### Output  
9 5 1 4 1 3  

#### Explanation  
Reversing the links turns `3 → 1 → 4 → 1 → 5 → 9` into `9 → 5 → 1 → 4 → 1 → 3`.  

### 2  

#### Input  
3  
100 200 300  

#### Output  
300 200 100  

#### Explanation  
The last node becomes the first after reversing.  

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
