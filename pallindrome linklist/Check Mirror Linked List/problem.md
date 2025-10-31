## Title  
Check Mirror Linked List  

## Slug  
check-mirror-linked-list  

## Difficulty  
Easy  

## Description  

A scientist records data points in a singly linked list.  
Determine if the recorded sequence forms a `mirror`, meaning the values appear identically when read backward.  

Return `true` if the sequence mirrors itself; otherwise, `false`.  

## Examples  

### 1  

#### Input  
5  
4 9 8 9 4  

#### Output  
true  

#### Explanation  
The list `4 → 9 → 8 → 9 → 4` forms a perfect mirror.  

### 2  

#### Input  
4  
2 5 5 1  

#### Output  
false  

#### Explanation  
The reverse order differs from the original, so it’s not mirrored.  

## Input Format  
- First line: integer n — number of nodes.  
- Second line: n integers for node values.  

## Output Format  
Return `true` if mirrored, else `false`.  

## Constraints  
- 1 ≤ n ≤ 1000  
- 0 ≤ node.val ≤ 1000  

## Time Limit  
1 second  

## Memory Limit  
512 MB  

## Tags  
linked-list
