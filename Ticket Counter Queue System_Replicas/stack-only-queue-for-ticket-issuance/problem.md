## Title
Stack Only Queue for Ticket Issuance

## Slug
stack-only-queue-for-ticket-issuance

## Difficulty
Easy

## Description

In a transportation ticketing infrastructure, passengers are processed strictly in the order in which they arrive, ensuring fair and predictable service delivery.

Although the required behavior follows a first come first served queue model, the underlying storage layer only provides stack based operations. Direct access to elements other than the top of a stack is not permitted.

To address this limitation, the system must simulate full queue functionality using exactly two stacks. The solution must correctly support adding new passengers to the back of the queue, removing passengers from the front, inspecting the front passenger without removal, and checking whether the queue is empty.

All supported operations must preserve FIFO ordering at all times while using only valid stack primitives. The implementation should also ensure efficient performance by achieving amortized constant time complexity per operation.
## Examples

## Input
["MyQueue", "push", "push", "peek", "pop", "empty"]
[ [], [1], [2], [], [], [] ]

## Output
[null, null, null, 1, 1, false]

## Explanation

Initialize the ticket counter queue
push(1) results in queue [1]
push(2) results in queue [1, 2]
peek returns 1
pop removes and returns 1, queue becomes [2]
empty returns false

## Input Format

Operations are provided as a list of method names.
Parameters for each operation are provided in a corresponding list.
Constructor calls have no parameters.

## Output Format

Return the result of each operation in order.
Constructor calls return null.
pop and peek return integers.
empty returns a boolean value.

## Constraints

1 <= x <= 9
At most 100 operations will be performed.
All calls to pop and peek are valid.

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

queue