## Title  

Print Files Sequence  

## Slug  

print-files-sequence  

## Difficulty  

Easy  

## Description  

Files are linked in a sequence for processing.  
Each node represents a file ID in a linked list.  
Your task is to print all file IDs in the order they are processed.  

Each ID should be printed separated by a space.  



## Examples  

### Example 1  

#### Input  
5  
11 22 33 44 55  

#### Output  
11 22 33 44 55  

#### Explanation  
Processing order:  
`Head -> 11 -> 22 -> 33 -> 44 -> 55 -> NULL`.  

### Example 2  

#### Input  
3  
100 200 300  

#### Output  
100 200 300  

#### Explanation  
Files processed in order.  

## Input Format  

- First line: integer `n`, number of files.  
- Second line: `n` integers representing file IDs.  

## Output Format  

Print all file IDs separated by spaces.  

## Constraints  

- 1 ≤ n ≤ 1000  
- 0 ≤ file ID ≤ 1000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

linked-list, traversal, printing
