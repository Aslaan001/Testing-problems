## Title  
Check Train Car Arrangement  

## Slug  
check-train-car-arrangement  

## Difficulty  
Easy  

## Description  

A train consists of cars labeled with numbers in a singly linked list.  
Determine whether the arrangement of train cars is `palindromic`, meaning it looks the same from the front and the back.  

Return `true` if it is, otherwise `false`.  

## Examples  

### 1  

#### Input  
5  
9 8 7 8 9  

#### Output  
true  

#### Explanation  
The order `9 → 8 → 7 → 8 → 9` looks identical both ways.  

### 2  

#### Input  
4  
2 3 4 5  

#### Output  
false  

#### Explanation  
The sequence changes when viewed in reverse.  

## Input Format  
- First line: integer n — number of train cars.  
- Second line: car labels.  

## Output Format  
Return `true` if the arrangement is palindromic, otherwise `false`.  

## Constraints  
- 1 ≤ n ≤ 1000  
- 0 ≤ node.val ≤ 1000  

## Time Limit  
1 second  

## Memory Limit  
512 MB  

## Tags  
linked-list
