## Title  
Flip the Train Cars  

## Slug  
flip-train-cars  

## Difficulty  
Easy  

## Description  

A train's cars are linked front-to-back as a singly linked list. To reroute the train, the engineer wants the last car to become the first.  

Given the head of the linked list of car identifiers, reverse the list and return the new head.  


## Examples  

### 1  

#### Input  
5  
10 20 30 40 50  

#### Output  
50 40 30 20 10  

#### Explanation  
Cars are reversed: last car (50) moves to the front.  


### 2  

#### Input  
4  
5 10 15 20  

#### Output  
20 15 10 5  

#### Explanation  
Train car order reversed.  


## Input Format  
- First line: integer n — the number of nodes in the linked list.  
- Second line: n integers representing the data values of each node.  

Note: The nodes are provided as a linked list in order.  


## Output Format  
Return the new head of the reversed linked list.

## Constraints  
- 1 ≤ n ≤ 1000  
- 0 ≤ node.val ≤ 1000  


## Time Limit  
1 second  

## Memory Limit  
512 MB  


## Tags  
linked-list, reverse, basic
