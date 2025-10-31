## Title  
Check Space Signal Pattern  

## Slug  
check-space-signal-pattern  

## Difficulty  
Easy  

## Description  

A sequence of space transmission signals is recorded as a linked list.  
Determine whether the signal sequence is `palindromic`, meaning it appears the same when reversed.  

Return `true` if it is, otherwise `false`.  

## Examples  

### 1  

#### Input  
5  
2 4 6 4 2  

#### Output  
true  

#### Explanation  
The signal `2 → 4 → 6 → 4 → 2` is identical in both directions.  

### 2  

#### Input  
4  
1 3 5 7  

#### Output  
false  

#### Explanation  
Reversing gives a different pattern.  

## Input Format  
- First line: integer n — number of signals.  
- Second line: signal values.  

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
