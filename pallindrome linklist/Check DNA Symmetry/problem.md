## Title  
Check DNA Symmetry  

## Slug  
check-dna-symmetry  

## Difficulty  
Easy  

## Description  

A biologist represents a DNA strand as a singly linked list of integers.  
Your task is to check whether the strand is `palindromic`, meaning it reads the same from both ends.  

Return `true` if the DNA sequence is symmetric, else `false`.  

## Examples  

### 1  

#### Input  
5  
1 3 5 3 1  

#### Output  
true  

#### Explanation  
The DNA strand `1 → 3 → 5 → 3 → 1` is palindromic.  

### 2  

#### Input  
4  
2 4 5 2  

#### Output  
false  

#### Explanation  
The sequence differs when reversed.  

## Input Format  
- First line: integer n — length of the DNA chain.  
- Second line: n integers for DNA bases.  

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
