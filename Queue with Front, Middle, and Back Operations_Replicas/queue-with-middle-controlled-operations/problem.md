## Title
Queue with Middle Controlled Operations

## Slug
queue-with-middle-controlled-operations

## Difficulty  
Easy  

## Description

In a processing pipeline manager, tasks must be managed in a queue where insertion and removal flexibility is essential for maintaining balanced execution.

Unlike traditional queues that only allow operations at the front or back, this structure also supports direct interaction with the middle position. This capability enables fine grained control over task prioritization and load distribution.

The queue supports inserting new elements at the front, at the exact middle position, or at the back. It also allows removing and retrieving elements from these same three positions while preserving a consistent definition of what constitutes the middle element.

When the number of elements in the queue is even, the middle position is defined as the element closer to the front. All operations must strictly adhere to this definition to ensure deterministic behavior.

The objective is to accurately implement this queue and ensure that every operation behaves exactly as specified while efficiently handling dynamic changes in queue size.
## Examples  

### 1  

#### Input  
6  
2 7 4 1 8 1  

#### Output  
1  

### 2  

#### Input  
1  
1  

#### Output  
1  

## Input Format  

- The first line contains an integer n — the number of stones in the warehouse  
- The second line contains n space-separated integers representing the weights of the stones  

## Output Format  

Return a single integer representing the weight of the last remaining stone.  
If no stones remain, return 0.

## Constraints  

1 ≤ n ≤ 30  
1 ≤ stone weight ≤ 1000  

## Time Limit  

1 second  

## Memory Limit  

512 MB  

## Tags  

priority-queue.  