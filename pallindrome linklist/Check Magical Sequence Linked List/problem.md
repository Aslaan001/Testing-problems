## Title  
Check Magical Sequence Linked List  

## Slug  
check-magical-sequence-linked-list  

## Difficulty  
Easy  

## Description  

A wizard creates a spell sequence represented as a singly linked list.  
You must check if the sequence of spell codes forms a `magical palindrome`, meaning it reads the same forward and backward.  

Return `true` if it does, otherwise `false`.  

## Examples  

### 1  

#### Input  
5  
7 5 3 5 7  

#### Output  
true  

#### Explanation  
The spell sequence `7 → 5 → 3 → 5 → 7` is identical when reversed.  

### 2  

#### Input  
4  
9 4 2 9  

#### Output  
false  

#### Explanation  
When reversed, `9 → 2 → 4 → 9` does not match the original.  

## Input Format  
- First line: integer n — number of spells.  
- Second line: n integers for each spell code.  

## Output Format  
Return `true` if magical, otherwise `false`.  

## Constraints  
- 1 ≤ n ≤ 1000  
- 0 ≤ node.val ≤ 1000  

## Time Limit  
1 second  

## Memory Limit  
512 MB  

## Tags  
linked-list
