## Title  
Check Robot Movement Pattern  

## Slug  
check-robot-movement-pattern  

## Difficulty  
Easy  

## Description  

A robot’s movement commands are stored as a linked list.  
Determine whether the command sequence is `reversible`, meaning the robot would follow the same path backward.  

Return `true` if the pattern is reversible, else `false`.  

## Examples  

### 1  

#### Input  
5  
1 4 7 4 1  

#### Output  
true  

#### Explanation  
The pattern `1 → 4 → 7 → 4 → 1` matches when reversed.  

### 2  

#### Input  
4  
3 6 9 6  

#### Output  
false  

#### Explanation  
The backward sequence differs from the original.  

## Input Format  
- First line: integer n — number of commands.  
- Second line: command sequence.  

## Output Format  
Return `true` if reversible, else `false`.  

## Constraints  
- 1 ≤ n ≤ 1000  
- 0 ≤ node.val ≤ 1000  

## Time Limit  
1 second  

## Memory Limit  
512 MB  

## Tags  
linked-list
