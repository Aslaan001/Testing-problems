## Title  

Print Pipeline Sections  

## Slug  

print-pipeline-sections  

## Difficulty  

Easy  

## Description  

A water pipeline is divided into several sections connected sequentially.  
Each node stores a section ID.  
Your task is to print all section IDs in order.  

Each ID should be printed separated by a space.  



## Examples  

### Example 1  

#### Input  
4  
10 20 30 40  

#### Output  
10 20 30 40  

#### Explanation  
Pipeline flow:  
`Source -> 10 -> 20 -> 30 -> 40 -> NULL`.  

### Example 2  

#### Input  
3  
7 8 9  

#### Output  
7 8 9  

#### Explanation  
`Source -> 7 -> 8 -> 9 -> NULL`.  

## Input Format  

- First line: integer `n`, number of sections.  
- Second line: `n` integers representing section IDs.  

## Output Format  

Print all section IDs separated by spaces.  

## Constraints  

- 1 ≤ n ≤ 1000  
- 0 ≤ section ID ≤ 1000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

linked-list, traversal, printing
