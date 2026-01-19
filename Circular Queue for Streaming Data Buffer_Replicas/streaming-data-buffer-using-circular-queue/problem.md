## Title
Streaming Data Buffer Using Circular Queue

## Slug
streaming-data-buffer-using-circular-queue

## Difficulty
Medium

## Description

In a real time data ingestion system, data arrives continuously and must be processed in the same order in which it is received. To manage memory efficiently and avoid unnecessary data movement, the system relies on a fixed size circular queue.

The queue follows a first in first out policy, ensuring that the earliest inserted element is always the first one to be removed. When the internal storage reaches the end of its allocated space, index positions wrap around to the beginning, allowing released slots to be reused seamlessly.

The system must support insertion of new elements, removal of existing elements, and inspection of the front and rear elements without altering the queue state. Additional checks are required to determine whether the queue is currently empty or has reached full capacity.

All operations must execute in constant time and strictly follow the defined behavior to ensure predictable performance in high frequency streaming environments.
## Examples

### 1

## Input
3 10
enQueue 1
enQueue 2
enQueue 3
enQueue 4
Rear
isFull
deQueue
enQueue 4
Rear
isEmpty

## Output
Yes
Yes
Yes
No
3
Yes
Yes
Yes
4
No

## Explanation

- Initialize the queue with capacity 3
- Insert 1, 2, 3 successfully
- Inserting 4 fails because the queue is full
- Rear returns 3
- isFull returns Yes
- Remove the front element
- Insert 4 successfully
- Rear now returns 4
- IsEmpty returns No

## Input Format

- The first operation initializes the circular queue with an integer k
- Subsequent operations call methods on the queue with their respective parameters

## Output Format

Return the result of each operation in the order they are executed.
Constructor calls return null.
Boolean results must be printed as Yes or No.

## Constraints

1 ≤ k ≤ 1000
0 ≤ value ≤ 1000
At most 3000 operations will be performed

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

queue