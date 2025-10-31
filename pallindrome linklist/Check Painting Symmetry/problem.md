## Title  
Check Painting Symmetry  

## Slug  
check-painting-symmetry  

## Difficulty  
Easy  

## Description  

An artist paints strokes represented as a linked list of brush IDs.  
Determine whether the painting pattern is `symmetric`, i.e., it looks the same on both sides.  

Return `true` if symmetric, otherwise `false`.  

## Examples  

### 1  

#### Input  
5  
8 6 4 6 8  

#### Output  
true  

#### Explanation  
The strokes `8 → 6 → 4 → 6 → 8` are mirrored.  

### 2  

#### Input  
4  
3 5 7 3  

#### Output  
false  

#### Explanation  
The pattern does not mirror correctly.  

## Input Format  
- First line: integer n — number of strokes.  
- Second line: stroke IDs.  

## Output Format  
Return `true` if symmetric, otherwise `false`.  

## Constraints  
- 1 ≤ n ≤ 1000  
- 0 ≤ node.val ≤ 1000  

## Time Limit  
1 second  

## Memory Limit  
512 MB  

## Tags  
linked-list
