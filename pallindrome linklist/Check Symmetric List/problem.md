## Title  
Check Symmetric Linked List  

## Slug  
check-symmetric-linked-list  

## Difficulty  
Easy  

## Description  

You are given the head of a singly linked list that stores numbers in sequence.  
Your task is to verify whether the sequence of numbers in the list is `symmetric`, meaning it reads the same backward and forward.  

If it is symmetric, return `true`; otherwise, return `false`.  

## Examples  

### 1  

#### Input  
5  
1 2 3 2 1  

#### Output  
true  

#### Explanation  
The list reads `1 → 2 → 3 → 2 → 1` in both directions, confirming symmetry.  

### 2  

#### Input  
4  
1 2 2 3  

#### Output  
false  

#### Explanation  
The order `1 → 2 → 2 → 3` changes when reversed. Hence, not symmetric.  

## Input Format  
- First line: integer n — the number of nodes in the linked list.  
- Second line: n integers representing the node values.  

## Output Format  
Return `true` if the linked list is symmetric, otherwise `false`.  

## Constraints  
- 1 ≤ n ≤ 1000  
- 0 ≤ node.val ≤ 1000  

## Time Limit  
1 second  

## Memory Limit  
512 MB  

## Tags  
linked-list
