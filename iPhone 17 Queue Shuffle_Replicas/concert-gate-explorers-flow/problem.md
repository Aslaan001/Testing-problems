## Title
Concert Gate Explorers Flow

## Slug
concert-gate-explorers-flow

## Difficulty
Easy

## Description
At the concert gate, a long queue of explorers awaits their turn. A new checkpoint opens at the very end of the line, which would let the last arrival go first. To keep fairness, the last k explorers are reordered by reversing only that segment, while the rest of the queue stays unchanged. If k is larger than the queue size, nothing changes.

## Examples

### 1
#### Input

q = [1, 2, 3, 4, 5], k = 3

#### Output

[1, 2, 5, 4, 3]

#### Explanation

The last 3 people [3, 4, 5] would be served unfairly if left as is (since 5 would go first). Reversing them to [5, 4, 3] restores fairness. Final queue: [1, 2, 5, 4, 3].

### 2
#### Input

q = [10, 20, 30, 40], k = 2

#### Output

[10, 20, 40, 30]

#### Explanation

The last 2 people [30, 40] are reversed into [40, 30], so 30 still gets served before 40 at the new counter.

## Input Format

- First line contains an integer n — the number of people in the queue.

- Second line contains n space-separated integers representing the queue elements (q[0] is the front, q[n-1] is the rear).

- Third line contains a single integer k, the number of people at the end of the queue to reverse.

## Output Format

Return the queue after reversing the last k elements, keeping the first n - k unchanged.

## Constraints

- 1 ≤ q[i] ≤ 10^5
- 1 ≤ n ≤ 10^5
- 1 ≤ k ≤ 10^5

## Time Limit
1 second

## Memory Limit
256 MB

## Tags
queue
