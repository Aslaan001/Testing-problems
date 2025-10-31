## Title  
Check Road Milestone Pattern  

## Slug  
check-road-milestone-pattern  

## Difficulty  
Easy  

## Description  

A highway’s milestones are recorded as a singly linked list.  
Check whether the milestone numbers form a `palindromic route`.  

Return `true` if the route is palindromic, otherwise `false`.  

## Examples  

### 1  

#### Input  
5  
1 2 3 2 1  

#### Output  
true  

#### Explanation  
The route `1 → 2 → 3 → 2 → 1` is the same forward and backward.  

### 2  

#### Input  
4  
4 6 7 8  

#### Output  
false  

#### Explanation  
The milestone order differs in reverse.  

## Input Format  
- First line: integer n — number of milestones.  
- Second line: milestone numbers.  

## Output Format  
Return `true` if palindromic, otherwise `false`.  

## Constraints  
- 1 ≤ n ≤ 1000  
- 0 ≤ node.val ≤ 1000  

## Time Limit  
1 second  

## Memory Limit  
512 MB  

## Tags  
linked-list
