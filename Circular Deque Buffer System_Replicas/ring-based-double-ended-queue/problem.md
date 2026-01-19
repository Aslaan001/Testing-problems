## Title
Ring Based Double Ended Queue

## Slug
ring-based-double-ended-queue

## Difficulty
Medium

## Description

In a low latency system component, it is necessary to manage a fixed size collection that supports insertion and removal of elements from both ends with predictable performance.

The structure operates as a double ended queue backed by a circular storage layout. When the front or rear index reaches the end of the allocated space, it wraps around to the beginning, allowing full utilization of the buffer capacity without shifting elements.

The system must support operations to insert elements at the front and rear, remove elements from both ends, and query the current front and rear values. Additional checks are required to determine whether the structure is currently empty or completely full.

All operations must follow strict behavioral rules and return appropriate results based on the current state of the deque. The implementation should ensure constant time performance for each operation while correctly managing index movement and capacity limits.
## Examples

## Input
["MyCircularDeque", "insertLast", "insertLast", "insertFront", "insertFront", "getRear", "isFull", "deleteLast", "insertFront", "getFront"]
[[3], [1], [2], [3], [4], [], [], [], [4], []]

## Output
[null, true, true, true, false, 2, true, true, true, 4]

## Explanation

Initialize the deque with capacity 3  
insertLast(1) → deque becomes [1]  
insertLast(2) → deque becomes [1, 2]  
insertFront(3) → deque becomes [3, 1, 2]  
insertFront(4) → fails because the deque is full  
getRear() → returns 2  
isFull() → returns true  
deleteLast() → removes 2  
insertFront(4) → deque becomes [4, 3, 1]  
getFront() → returns 4  

## Input Format

Operations are provided as a list of method names.  
Parameters for each operation are provided in a corresponding list.  
Constructor calls contain a single integer parameter.  

## Output Format

Return the result of each operation in order.  
Constructor calls return null.  
Insert and delete operations return boolean values.  
Get operations return integers.

## Constraints

1 <= k <= 1000  
0 <= value <= 1000  
At most 2000 total operations will be performed  

## Time Limit

1 second

## Memory Limit

512 MB

## Tags
 
queue  
 