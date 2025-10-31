## Title  
Check Treasure Map Path  

## Slug  
check-treasure-map-path  

## Difficulty  
Easy  

## Description  

An explorer follows a path marked on a treasure map, stored as a linked list.  
Determine if the path forms a `looping trail`, meaning it reads the same forward and backward.  

Return `true` if the path loops symmetrically, otherwise `false`.  

## Examples  

### 1  

#### Input  
5  
1 3 5 3 1  

#### Output  
true  

#### Explanation  
The path `1 → 3 → 5 → 3 → 1` loops perfectly.  

### 2  

#### Input  
4  
2 4 6 8  

#### Output  
false  

#### Explanation  
The trail is not identical backward.  

## Input Format  
- First line: integer n — number of path points.  
- Second line: sequence of path identifiers.  

## Output Format  
Return `true` if the path loops symmetrically, otherwise `false`.  

## Constraints  
- 1 ≤ n ≤ 1000  
- 0 ≤ node.val ≤ 1000  

## Time Limit  
1 second  

## Memory Limit  
512 MB  

## Tags  
linked-list
