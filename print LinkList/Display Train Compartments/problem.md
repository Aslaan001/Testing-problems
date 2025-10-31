## Title  

Display Train Compartments  

## Slug  

display-train-compartments  

## Difficulty  

Easy  

## Description  

Each compartment in a train is connected sequentially forming a `linked list`.  
Given the `head` of the train, print the `IDs` of all compartments from front to back.  

Each ID should be printed `separated by a space`.  

## Examples  

### Example 1  

#### Input  
3  
101 102 103  

#### Output  
101 102 103  

#### Explanation  
Train sequence: `engine -> 101 -> 102 -> 103 -> NULL`.  
We print the compartment IDs in order.

### Example 2  

#### Input  
4  
201 202 203 204  

#### Output  
201 202 203 204  

#### Explanation  
Train compartments appear in order as above.


## Input Format  

- First line: integer `n`, number of compartments.  
- Second line: `n` integers representing IDs from engine to tail.  

## Output Format  

Print all compartment IDs separated by spaces.  

## Constraints  

- 1 ≤ n ≤ 1000  
- 0 ≤ ID ≤ 1000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

linked-list, traversal, printing
