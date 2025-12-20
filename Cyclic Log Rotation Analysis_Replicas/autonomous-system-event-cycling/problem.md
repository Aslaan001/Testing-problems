## Title

Autonomous System Event Cycling

## Slug

autonomous-system-event-cycling

## Difficulty

Hard

## Description

In a mission-critical analytics pipeline, ordered signals are aggregated into a linearized log to
support downstream processing and replay. To validate deterministic behavior under reordering,
engineers apply cyclic transformations that rotate a suffix of the signal sequence to the front.
For a given starting sequence, a required ending sequence, and a fixed number of enforced
transformations, the pipeline must enumerate all valid transformation strategies. Each
transformation is uniquely defined by how many trailing elements are repositioned.  Your objective
is to calculate how many distinct transformation strategies satisfy the constraints. The result is
used to evaluate robustness of scheduling logic and correctness of transformation APIs.

## Examples

### 1

#### Input
abcd  
cdab  
2

#### Output
2

#### Explanation

There are two valid sequences of operations that transform `s` into `t` in exactly two steps.

### 2

#### Input
ababab  
ababab  
1

#### Output
2

#### Explanation

Two different suffix choices result in the same string, but are counted as separate operations.

## Input Format

- First line: string `s`
- Second line: string `t`
- Third line: integer `k`

## Output Format

- Return a single integer — the number of valid transformation sequences modulo `10^9 + 7`

## Constraints

- 2 ≤ n ≤ 5 × 10^5
- 1 ≤ k ≤ 10^15
- `s.length == t.length`
- `s` and `t` consist only of lowercase English letters

## Time Limit

1 second

## Memory Limit

512 MB

## Tags

dynamic-programming  
